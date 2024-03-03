# Identificación de Outliers 
- De acuerdo con lo indicado por la Entidad Regulatoria Senasa, las instalaciones deben tener condiciones adecuadas de iluminación, temperatura, humedad, ventilación y ruidos que no
  afecten adversamente, directa o indirectamente a las personas, al producto fabricado o al funcionamiento de los equipos.
- En este caso, se obtienen los datos a partir de sensores marca Testo instalados en el depósito de los productos terminado SELLLADORES y DETERGENTES. Presentados en formato .CSV.
- Se utiliza como criterio para identificación de Outliers el Método Tres Sigma.
- Se llevan a cabo los pasos descritos a continuación con la finalidad de demostrar cumplimiento con la Norma:

## Obtención de Datos
### Importación de Datos
- Cada Hoja de Excel contiene los datos de TEMPERATURA y HUMEDAD, para el área de almacenamiento de producto terminado Selladores y Detergentes, respectivamente:
![No carga la imagen](https://github.com/ruizrlaurap0704/PowerBI/blob/main/Obtenci%C3%B3n%20de%20Datos.png)

### Limpieza y filtrado de Datos
- Se crean tablas para dar formato a una lista de datos, ordenar, filtrar, organizar y lograr ver los mismos de forma sencilla.
- Antes de crear la tabla deben verificarse y, muchas veces, realizar una limpieza de los datos y la imputación de datos faltantes.
- Cada fila debe contener los detalles de un registro e incluir un identificador único para cada fila, en este caso el mes.
- En la primera fila de la lista, cada columna debe tener un encabezado.
- La lista no debe tener filas en blanco ni columnas completamente en blanco.
- Esta etapa se realiza a nivel de PowerQuery.

### Normalizaciones
El objetivo es poder aprovechar al máximo las ventajas de un modelo de datos homogeneizando el formato en el cual se presentan los datos. 

## Análisis de Datos
- Se implementan fórmulas y columnas calculadas con DAX para realizar cálculos sobre los datos. En este caso, máximos y mínimos para identifica Outliers en base al Método Tres Sigma.
- Indicadores, Estadísticas, Medidas, Diagramas y KPIs. 

## Visualización
Power BI facilita la creación de informes interactivos, de vistas analíticas y de tableros. Además pueden realizarse exploraciones geoespaciales con el objetivo de poder trazar mapas.
- Paneles o Dashboards: Uso de Filtros básicos, avanzados y Top N, Mapas, Tablas, Gráficos Torta, Grafico Barras, Histograma. 


