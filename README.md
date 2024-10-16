# Adidas-Sales-Excel-Dashboard
Proyecto de análisis de datos en Excel que contiene los siguientes documentos: 

-Adidas US Sales Dashboard_v.1

-Adidas US Sales Datasets_v.1


Durante el proyecto se han realizado las siguientes actividades:

-Transformación y limpieza

-Analisis descriptivo de los datos

-Dashboard

-Descripción del proceso (Incluido en este archivo README)

-Informe del análisis (Incluido en este archivo README)


Descripción del proceso:

1.Se extrae desde Kaggle.com un fichero de datos llamado Adidas US Sales Datasets
2.Se realiza un preanálisis y se detecta un rango de 13 columnas y 9648 filas. Las columnas son las siguientes: 
- Retailer
- Retailer ID
- Invoice Date
- Region
- State
- City
- Product
- Price per Unit
- Units Sold
- Total Sales
- Operating Profit
- Operating Margin
- Sales Method
3. Se convierte el rango de datos a una tabla llamada "sales_data"
4. Se validan los duplicados. Para hacer esto aplicamos un formato condicional en la columna sale_id. No se encuentran duplicados pero para hacer una doble comprobación se crea la columna "duplicate" en la tabla "sales_data". Además se crea la página check for duplicates para contar los registros duplicados que muestra la columna creada. Este valor es 0 y se muestra que no hay duplicados. En caso de haberse encontrado se hubiese seleccionado la opción datos>herramientas de datos>quitar duplicados.
5. Se convierte el formato numeroco de las columnas de personalizado a numerico contabilidad en dolares americanos.
6. Análisis descriptivo de los datos a través de tablas dinámicas. Creación de los kpi y de distribuciones que tienen impacto en el estudio del negocio.
7. Creación de un dashboard dinamico con KPI y distribuciones creadas previamente y creación de filtros adicionales mediante segmentadores de datos.
7. Creation of a dynamic dashboard with kpi and distributions from the analysis and addition of filters.
8. Simulación de la incorporación de datos adicionales al análisis. Para practicar la actualización del dashboard se genera un fichero de datos temporalmente posterior a los iniciales con valores aleatorios y se actualizan los datos de las tablas dinámicas para comprobar su correcto funcionamiento.


  Informe del análisis:

Se ha construido un cuadro de mando para la empresa Adidas con el objetivo de analizar las ventas de la empresa y sus resultados operativos en los distintos estados de E.E.U.U. a través de los principales distribuidores por los cuales Adidas llega a sus clientes.
Para tener una visión en profundidad del negocio de Adidas se han diseñado una serie de KPIs, Distribuciones y filtros que nos permiten analizar de forma dinámica los datos y poder obtener información relevante para la toma de decisiones. A continuación se procede a explicar los componentes del cuadro de mando.

Los KPI son los siguientes:
1. Total Sales: Calcula la suma total de la difra de ventas de la empresa.
2. Operating profit: Calcula la suma total  beneficio operativo de las ventas.
3. Operating Margin: Calcula el margen operativo agregado del total de beneficio operativo sobre la cifra de ventas de forma porcentual.
4. Units Sold: Calcula la suma total de unidades vendidas.
5. Price per Unit: Calcula la media de los precios por unidad de los productos vendidos.

Las distribuciones son las siguientes: 


  
  
