# Proyecto Acuífero Morroa – Análisis y Procesamiento de Datos Hidrogeológicos
---

##  Descripción del Proyecto

Este repositorio alberga el **componente de investigación, procesamiento y análisis de datos** del proyecto *"Aplicativo Web Interactivo para la Visualización y Análisis de Datos Hidrogeológicos del Acuífero Morroa"*.

El acuífero Morroa, distribuido entre los departamentos de Sucre y Córdoba, es la principal fuente de abastecimiento hídrico para el 98% de la población bajo la jurisdicción de CARSUCRE. Sin embargo, la sobreexplotación y la falta de herramientas accesibles para interpretar los datos piezométricos generan una brecha entre la información técnica disponible y la toma de decisiones.

En esta etapa inicial del proyecto, el repositorio contiene:

- **Análisis bibliométrico** del estado del arte en hidrogeología, modelos predictivos y monitoreo de acuíferos.
- **Registros históricos** de niveles piezométricos del acuífero Morroa (2010-2026).
- **Notebooks de procesamiento y análisis** de series temporales.
- **Análisis de correlación** con variables ambientales (NDVI, EVI, precipitación CHIRPS).
- **Exploración de patentes IoT** aplicadas al monitoreo de aguas subterráneas.

---

## Estructura del Repositorio

```plaintext
Proyecto-Acuifero-Morroa/
│
├── Bibliometria/                          # Análisis bibliométrico y mapeo científico
│   ├── WoS_458 Completa/
│   │   ├── 2015-2017/
│   │   │   └── Data/
│   │   │       └── savedrecs_2015-2017.txt
│   │   ├── 2020-2021/
│   │   │   └── Data/
│   │   │       └── savedrecs_2020_2021.txt
│   │   ├── 2024 Trends/
│   │   │   ├── Data/
│   │   │   │   └── download_2024_Trends.txt
│   │   │   ├── Salida/
│   │   │   │   ├── doi_51.list
│   │   │   │   └── download2024u51.txt
│   │   │   └── Tratamiento/
│   │   │       ├── 49.graphml
│   │   │       ├── CitationBurst.in
│   │   │       ├── CitationBurst.out
│   │   │       ├── citespace.config.json
│   │   │       ├── citespace.parameters
│   │   │       ├── citespace.signature.json
│   │   │       ├── cluster_labels.tsv
│   │   │       └── narrative_summary.html
│   │   ├── BD Completa/
│   │   ├── BD Refinada.png
│   │   ├── Mapping_Knowledge_in_the_...
│   │   ├── MicroTopics Elegidos Pag1.png
│   │   ├── MicroTopics Elegidos Pag2.png
│   │   └── MicroTopics Elegidos Pag3.png
│   ├── Annual_Production_bibliometrix_2024-11-13.xlsx
│   ├── BD WoS RS1.xls
│   └── scopus_1603.csv
│
├──  Datos/                                # Datos hidrogeológicos históricos
│   └── Pozos/
│       └── Final Serie_Indices_Sincronizado...
│
├──  algoritmos/                           # Notebooks y scripts de análisis
│   ├── análisis de pozos/
│   │   └── Pozos_Analisis.ipynb
│   ├── controlador/
│   │   └── Controlador_Pozo2.ipynb
│   ├── correlacion/
│   │   └── Analisis_NE_NDVI_EVI_CHIRPS...ipynb
│   ├── graficos/
│   │   └── GraficosPozosTesis.ipynb
│   └── patentes/
│       └── Patentes.ipynb
│
└──  patentes iot/                         # Exploración de patentes IoT aplicadas
    ├── Filtrin gp-search-20260516-205825.xlsx
    └── reporte_cpc_patentes.xlsx
