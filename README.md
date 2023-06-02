# TRABAJO-FINAL-PROGRA

El link al repositorio es el siguiente: https://github.com/Germiprogramer/TRABAJO-FINAL-PROGRA.git

Paralelización con Dask:



Distrubución de Datos y trabajo:



Correlaciones y análisis de algoritmos en paralelo:

Este apartado ya está resuelto en documento científico de la entrega, pero quiero desarrollar un problema surgido. A la hora de elegir las columnas, se me olvidó quita passenger_count, que es prácticamente similar a adjusted_passenger_count. Por ello, ambos algoritmos empleados daban un r2 score altísimo, de 0,99. Al corregir dicho error, el r2 score ya daba datos normales, 0,24 para la regresión multilineal y 0,76 para el random forest. Por tanto, el único algoritmo apto para el trabajo es el Random Forest. Las variables no siguen una relación lineal, y el random forest es mejor debido a que no trabaja únicamente con relaciones lineales y aditivas. Además, también se podría haber usado variables categoricas, pero no ha sido el caso en este trabajo.
