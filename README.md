# Proyecto Acuífero Morroa – Análisis y Procesamiento de Datos Hidrogeológicos

## Descripción del Proyecto

Este repositorio alberga el componente de investigación, procesamiento y análisis de datos del proyecto *“Aplicativo Web Interactivo para la Visualización y Análisis de Datos Hidrogeológicos del Acuífero Morroa”*.

El acuífero Morroa, distribuido entre los departamentos de Sucre y Córdoba, es una fuente principal de abastecimiento hídrico para la población bajo la jurisdicción de CARSUCRE. La sobreexplotación y la falta de herramientas accesibles para interpretar los datos piezométricos generan una brecha entre la información técnica disponible y la toma de decisiones.

En esta etapa, el repositorio contiene:

- Análisis bibliométrico del estado del arte en hidrogeología.
- Registros históricos de niveles piezométricos del acuífero Morroa.
- Notebooks de procesamiento y análisis de series temporales.
- Análisis de correlación con variables ambientales.
- Exploración de patentes IoT aplicadas al monitoreo de aguas subterráneas.
- Anexos técnicos entregados por el docente.

## Estructura del Repositorio

```text
Proyecto-Acuifero-Morroa/
│
├── algoritmos/                              # Notebooks y scripts de análisis
│   ├── análisis de pozos/
│   │   └── Pozos_Analisis.ipynb
│   ├── controlador/
│   │   └── Controlador_Pozo2.ipynb
│   ├── correlacion/
│   │   └── Analisis_NE_NDVI_EVI_CHIRPS.ipynb
│   ├── graficos/
│   │   └── GraficosPozosTesis.ipynb
│   └── patentes/
│       └── Patentes.ipynb
│
├── Bibliometria/                            # Análisis bibliométrico
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
├── Datos/                                   # Datos hidrogeológicos históricos
│   └── Pozos/
│       └── Final Serie_Indices_Sincronizado...
│
├── anexos/                                  # Anexos técnicos 
│   ├── Anexo 2/
│   │   ├── cambio_nivel Completo 2010-2025 Pozos.png
│   │   ├── Imputación Tabla-Comparación pozos.xlsx
│   │   └── Listado de los Pozos_RESUME.xlsx
│   ├── Anexo 3/
│   │   └── Anexo_3_Validacion_Estadistica_Imputacion.xlsx
│   ├── Anexo 4/
│   │   └── Anexo 4 Ajuste Suavizadores.xlsx
│   ├── Anexo 5/
│   │   └── Anexo 5 Validacion Estadistica Suavizadores.xlsx
│   ├── Anexo 6/
│   │   └── Anexo 6 Datos pozos Gradientes.xlsx
│   ├── Anexo 7/
│   │   └── Anexo 7 Analisis Profundo Gradientes.xlsx
│   ├── Anexo 8/
│   │   ├── Anexo 8 Validacion Multivariada Clustering.pdf
│   │   └── Anexo 8 Validacion Multivariada Clustering.xlsx
│   ├── Anexo 9/
│   │   └── Anexo 9 Métricas Clusters Por Pozo por Pozo.xlsx
│   ├── Anexo 10/
│   │   ├── Anexo 10 Validacion ISAC.pdf
│   │   └── Anexo 10 Validacion ISAC.xlsx
│   ├── Anexo 11/
│   │   └── Anexo 11 Resultados_Tesis ICMP v2.xlsx
│   ├── Anexo 12/
│   │   ├── Anexo 12 Resultados_Tesis (general) ICMP Ranking Sperman.xlsx
│   │   ├── Anexo 12 Robustez Ranking IMCP.pdf
│   │   └── Anexo 12 Robustez Ranking IMCP.xlsx
│   ├── Anexo 13/
│   │   ├── Anexo 13 Robustez MonteCarlo IMCP.pdf
│   │   └── Anexo 13 Robustez MonteCarlo IMCP.xlsx
│   ├── Anexo 14/
│   │   ├── Anexo 14 Sensibilidad Global IMCP.pdf
│   │   └── Anexo 14 Sensibilidad Global IMCP.xlsx
│   ├── Anexo 15/
│   │   ├── Anexo 15 Validacion Bootstrap IMCP.pdf
│   │   ├── Anexo 15 Validacion Bootstrap IMCP.xlsx
│   │   ├── ITA - validación independiente de las tendencias.pptx
│   │   └── Resultados ITA 17 pozos/
│   │       ├── ITA_17_pozos_Morroa.png
│   │       └── Resumen_ITA_17_pozos.xlsx
│   ├── Anexo 16/
│   │   └── Anexo 16 Analisis Temporal Niveles Caudales Pozos CARSUCRE.pdf
│   ├── Anexo 17/
│   │   ├── Anexo 17 Analisis Dinamica Indices Espectrales.pdf
│   │   └── Anexo_17_Analisis_Indices_Espectrales.xlsx
│   ├── Anexo 19/
│   │   └── Anexo 19 Correlacion Precipitacion GWSA Actualizado.pdf
│   └── Anexo 20/
│       └── Anexo 20 Control Optimizacion Gemelo Digital.pdf
│
├── patentes iot/                            # Patentes IoT aplicadas al monitoreo
│   ├── Filtrin gp-search-20260516-205825.xlsx
│   └── reporte_cpc_patentes.xlsx
│
└── README.md                                # Documentación general del proyecto
```

