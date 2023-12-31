# AumentoResolucion_modelosMesoescala

En este repositorio se presentan los códigos utilizados para llevar a cabo la metodología presentada en la tesis 'Estudio del Aumento de la resolución espacial de modelos mesoescala para el análisis del recurso eólico'

### A continuación se presenta un pequeño resumen de cada código utilizado.

- ***gus_wrf_ray.py***:
  Es el script base para utilizar las rutinas de la librería Iris para la lectura y extracción de datos de los modelos mesoescala de WRF.
- ***STD_D_IB_VMC.ipynb***: Es el cuaderno de jupyter para la obtención de las series temporales mediante los métodos de interpolación para el dominio ’D’.
- ***Coef_Corr_D.ipynb***: Es el código muestra para la obtención los coeficientes de correlación de spearman diarios para el dominio ’D’.
- ***Extract100.ipynb***: Es el código muestra para la obtención del conjunto de datos con una resolución de 100 metros para una sola hora para el dominio 'D' mediante interpolación bilinear e interpolación de vecino más cercano.
- ***Extrac_VMC_D.ipynb***: Es el código muestra para la extracción de los datos de los modelos mesoescala con la resolución espacial de 1 kilómetro para el dominio ’D’.
- ***Calc_D_Min_May_2016.ipynb*** Es el código muestra para la lectura y procedimiento para realizar el aumento de la resolución espacial para el dominio ’D’ para una sola hora. Así como la obtención de las series temporales diarias, la obtención de métricas de correlación y los factores de planta.
