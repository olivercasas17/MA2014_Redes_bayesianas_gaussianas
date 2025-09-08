# MA2014_Redes_bayesianas_gaussianas

Este proyecto utiliza datos de la Encuesta Nacional de Salud y Nutrición (ENSANUT) 2022 del INEGI y datos de calidad del aire del 2025 de la SEMARNAT para modelar las relaciones entre contaminantes atmosféricos y biomarcadores de salud mediante redes bayesianas gaussianas en R.

Se construyeron tres DAGs diferentes para modelar las interacciones entre contaminantes del aire (SO₂, CO, NOₓ, COV, PM10, PM2.5, NH₃) y biomarcadores de salud (albúmina, HDL, LDL, creatinina, glucosa, insulina, PCR, triglicéridos, HbA1c, EAG). Los modelos se compararon utilizando criterios AIC y BIC para seleccionar el de mejor ajuste y realizar inferencias probabilísticas sobre el impacto de la contaminación atmosférica en la salud.

**Herramientas:** R, bnlearn, tidyverse, Rgraphviz

## Colaboradores
- [@olivercasas17](https://github.com/olivercasas17)  
- [@ErikJajan](https://github.com/ErikJajan)  
- [@JoseLuis-tsm](https://github.com/JoseLuis-tsm)