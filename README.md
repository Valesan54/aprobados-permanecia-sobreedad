## Aprobados, permanencia y sobreedad
Herramientas básicas para el Análisis de Datos

Moscoso Valeria Sandra

## Objetivos ##: Identificar puntos críticos en las trayectorias escolares primarias

Análisis de datos **SIMULADOS** relacionados con la repitencia y sobreedad en las escuelas primarias de PBA.Los mismos **NO** reflejan información de la DGCyE de la pcia  de Bs.As.

Se trabajó con un CSV que contenía todos los datos relevados por las escuelas primarias de diversos distritos de la Provincia de Buenos Aires.
Link: https://docs.google.com/spreadsheets/d/1uXuMBD8ju75vkUFmcyO70LxNBgjq-EIccxZLkxUyhnc/edit?usp=sharing

Los datos fueron analizados en Google Colab utilizando diversas librerías de Python. Link:https://colab.research.google.com/drive/1s9ekq8b455SVCTk3YSYuTV2cCJp5J9g5?usp=sharing

**Preparación de datos:** Se realizó un diagnóstico inicial (`.info()`, `.isna().sum()`, `.duplicated().sum()`, `.nunique()`, `.describe()`) y se limpiaron los datos. Esto incluyó la conversión de columnas de porcentaje a tipo numérico y el manejo de valores nulos (se eliminaron las filas con nulos).

A lo largo de este análisis, se formularon preguntas de investigación específicas que guiaron la exploración de los datos. Para responder a estos interrogantes, se utilizaron diversas visualizaciones gráficas, incluyendo gráficos de barras, gráficos de líneas y diagramas de dispersión.

Por último, se elabora en Power BI una presentación que consta de 2 folios:
* En el primero se expone la información concentrada en 3 tarjetas puntuales. Respondiendo de forma sintética de donde surgen los datos ejecutados en Google Colab
* En el segundo se desglosa la información por distrito y por escuela.
