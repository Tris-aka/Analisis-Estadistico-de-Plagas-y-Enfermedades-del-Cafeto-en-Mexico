# Analisis-Estadistico-de-Plagas-y-Enfermedades-del-Cafeto-en-Mexico

Se analizan datos de la SENASICA y SADER para conocer como fueron afectadas las plantaciones de cafeto en 3 de los estados más importantes en su producción en México, los cuales son Chiapas, Veracruz y Puebla, en los años 2016-2018. Se utilizaron datos de la NASA para relacionar las tendencias con variables atmosféricas.

## Motivación

En algunos estados de México la producción de cafeto es de gran importancia económica y cultural, por lo que monitorear las enfermedades y plagas que afectan a estas plantas es una labor que se lleva a cabo cotidianamente, por ejemplo, mediante revisiones especializadas que evaluan el tipo y la gravedad del daño que sufren las plantaciones. Estos datos se encuentran reportados en bases de datos como SENASICA y SADER.

En este proyecto nos centramos en los estados de Chiapas, Veracruz y Puebla durante los años 2016, 2017 y 2018. Esto debido a la importancia económica en dichos estados, además de que en este periodo de tiempo los periodos en los que no se reportan valores es mínima a comparación de años más recientes.

Se busca encontrar relaciones entre variables atmosféricas y la predominancia de las distintas plagas y enfermedades, además de conocer si es que en este periodo hubo alguna epidemia de importancia económica según los reportes en las bases de datos.

## Métodos

El análisis se llevo a cabo en el lenguaje Python, con el cual se llevó a cabo un análisis explorativo de los datos con el fin de limpiar lo que fuera necesario. Posteriormente se filtraron los datos en repetidas ocasiones para obtener gráficas y valores de interés, como encontrar y graficar la variabilidad en severidad en la planta promedio por mes para cada uno de los estados o correlacionar mediante coeficiente de Pearson variables atmosféricas con el porcentaje de afectación de la roya.

Las librerías principales fueron Pandas, NumPy y Matplotlib.

## Resultados

Según el análisis realizado no se identificó ninguna epidemia de importancia económica, además de que se pudieron correlacionar satisfactoriamente las variables atmosféricas de temperatura, precipitación y humedad relativa con la presencia de la roya en la planta para cada año y estado.
