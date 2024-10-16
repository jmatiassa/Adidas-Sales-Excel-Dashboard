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

1. Operating performance by quarter: Distribución temporal de la cifra de ventas y el beneficio operativo divididos por trimestresen un gráfico lineal.
2. Distribution of total sales and operating profit by distributor: Distribución que agrupa las ventas totales y el beneficio operativo para cada distribuidor en un gráfico de columnas agrupadas.
3. Distribution of operating margin by distributor: Distribución que agrupa los márgenes operativos para cada distribuidor en un gráfico de columnas. Para ello se crea un nuevo campo en la tabla dinámica para calcular el margen dividiendo el beneficio operativo entre la cifra de ventas, de forma que calcule un total para cada fila seleccionada; en este caso el distribuidor.
4. Distribution of units sold by product: Distribución que agrupa el total de unidades vendidas para cada producto en un diagrama circular.
5. Distribution of opperating margin by sales method: Distribución que agrupa el margen total de beneficio para canal de distribución mediante un diagrama circular de anillos.
6. Distribution of total sales and opperating profit by product: Distribució que agrupa el total de cifra de ventas y el beneficio operativo para cada producto vendido mediante un gráfico de columnas agrupadas.
7. Distribution of operating margin by product: Distribución que agrupa los márgenes operativos para cada producto en un gráfico de columnas.

Los filtros dan dinamismo al gráfico permitiendo ampliar la profunididad del análisis desde diferentes enfoques. Los filtros son los siguientes:
1. Filtro de month: permite filtrar por mes.
2. Filtro de Year: permite filtrar por año.
3. Filtro de quarter: permite filtrar por trimestres.
4. Filtro de Product: permite filtrar por categoría de producto.
5. Filtro de Retailer: permite filtrar por distribuidor.
6. Filtro de State: permite filtrar por estado del país.

Se ha realizado un análisis del negocio para poner a prueba la funcionalidad del dashboard de analítica y se han detectado los siguientes puntos: 
1. Análisis general del negocio
![image](https://github.com/user-attachments/assets/0a909441-34ea-4e94-bfd6-711986c91730)


Mediante el análisis de los principales indicadores (KPI) del negocio detectamos que del total de ventas de más de 1,1M$ el beneficio operativo es de 465M$, equivalente a un margen operativo de 37%. Estos resultados vienen dados por un volumen de ventas de 2,5M de unidades vendidas a un precio medio por unidad de 45$. Para analizar en detalle estos datos procedemos a analizar las distribuciones.
2. Análisis temporal del negocio
![image](https://github.com/user-attachments/assets/4398a39e-0c19-463e-acf1-096fef1b44d3)

Mediante el análisis de la evolución del rendimiento operativo por trimestre detectamos que tanto el beneficio operativo como la cifra de ventas han tenido una tendencia similar. Se visualiza un pico en las ventas en el año 2021 y una tendencia alcista de forma general. Estos datos son una muestra de práctica y no tienen por que tener una explicación lógica pero podemos establecer una hipótesis sobre un crecimiento tan radical en las ventas 




  
  
