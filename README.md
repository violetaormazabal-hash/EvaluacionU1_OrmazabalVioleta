# Evaluación 1: Análisis de Deflexión en Viga Simplemente Apoyada

Este repositorio contiene el flujo de trabajo reproducible para analizar el comportamiento elástico lineal de una viga sometida a carga puntual, comparando datos sintéticos medidos con la predicción teórica de Euler-Bernoulli.

## Estructura del Proyecto

- `data/`: Contiene los archivos originales provistos (`datos_viga.csv`, `parametros_viga.xlsx`, `esquema_viga.png`). Estos archivos se conservan intactos.
- `analysis/`: Contiene la planilla `analisis_viga.xlsx` con la conversión de unidades al Sistema Internacional (SI), el cálculo de inercia, la determinación de la deflexión teórica y el cálculo de la diferencia relativa.
- `figures/`: Contiene el gráfico `carga_deflexion.png` que compara los datos medidos y teóricos.
- `report/`: Contiene el código fuente en LaTeX (`main.tex`, `main_sections.tex`, `bibfile.bib`) y el documento PDF final compilado.
- `USO_IA.md`: Declaración detallada del uso de inteligencia artificial en este trabajo.

## Instrucciones de Reproducción

1. Los datos originales (entradas) se encuentran en la carpeta `data`.
2. Para revisar los cálculos y transformaciones, abra `analysis/analisis_viga.xlsx`. Las celdas de cálculo contienen las fórmulas explícitas referenciadas estrictamente a los parámetros convertidos al SI. El gráfico se alimenta dinámicamente de estas celdas.
3. Para compilar el informe, procese el contenido de la carpeta `report` (vinculando la imagen de `figures`) en un compilador de LaTeX estándar, estableciendo `main.tex` como archivo principal.
