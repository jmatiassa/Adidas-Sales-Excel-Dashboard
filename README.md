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

  ![image](https://github.com/user-attachments/assets/16515589-0ef9-4125-94e7-9f6d43586e6a)



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

Se ha realizado un análisis de las ventas de los años 2020 y 2021, excluyendo los datos del año 2022 ya que no representan una imagen fiel del negocio si no que han sido una práctica para añadir los datos al modelo. El objetivo de este análisis es poner a prueba la capacidad de obtención de información de la herramienta y a continuación se muestran los resultados:
1. Análisis general del negocio
   

![image](https://github.com/user-attachments/assets/352ad028-9723-4b3d-802b-6500a1b63ee3)




Mediante el análisis de los principales indicadores (KPI) del negocio se detecta que del total de ventas es de aproximadamente 900K$ y el beneficio operativo es de 332K$, equivalente a un margen operativo de 37%. Estos resultados vienen dados por un volumen de ventas de 2.5M unidades vendidas a un precio medio por unidad de 45$. Para analizar en detalle estos datos se procede a analizar las distribuciones.

2. Análisis temporal del negocio

![image](https://github.com/user-attachments/assets/5e0bd656-cba2-4b5b-afe1-d127553e9c10)



En el análisis de la evolución del rendimiento operativo por trimestre se detecta que tanto el beneficio operativo como la cifra de ventas han tenido una tendencia similar. Se visualiza un pico en las ventas en el año 2021 y una tendencia alcista de forma general. Estos datos son una muestra de práctica y no tienen por que tener una explicación lógica pero se puede establecer una hipótesis sobre un crecimiento en las ventas. Para ello se analiza en profundidad el año 2020 seleccionando este valor en el filtro y se compara con el año 2021.

![image](https://github.com/user-attachments/assets/9e3b1d99-1edb-4094-a1ba-95e2b5ce5927)



Durante el año 2020 las ventas trimestrales se mantienen constantes alrededor de los 50M salvo una bajada en el 4º trimestre a los 27K$. Visualizando el resto del dashboard se analiza que del total de unidades vendidas que se han visto anteriormente (2,5K), solo 460K se vendieron en este año. Estos productos fueron distribuidos por West Gear, Foot Locker Walmart, Sports Direct y Kohl's siendo West Gear el máximo distribuidor con una cifra de ventas de 90M$. 

![image](https://github.com/user-attachments/assets/198ebb0c-0652-48a1-8e73-8d86e8b5723b)



Comparando los resultados del año 2020 con el año 2021 detectamos que a partir del 1er trimestre ya se visualiza un salto en ventas llegando hasta los 150M$ e incrementándose hasta los 190M$ en el 4º trimestre. Al comparar la distribución ventas por proveedor se visualizan variaciones notables en la lista de distribuidores y en sus ventas. En este momento Foot Locker se situa como el máximo distribuidor en cifra de ventas con 177M$ de cifra de negocio. Adicionalmente al crecimiento general en las ventas detectamos la entrada de Amazon como distribuidor. 

Además del análisis de los distribuidores podemos comprobar que las ventas de los productos de Adidas han crecido de forma homogénea y no hay diferencias entre los tipos de productos vendidos anterior y posteriormente. Vemos un incremento en todas las líneas de la marca y por lo tanto se detecta que hay un aumento agregado en la marca, sin focalizarse en una línea de productos en particular.

Con este análisis, viendo un crecimiento de las ventas en todos los distribuidores, pasando de una cifra de negocios de 182M$  en 2020 a 717M$ en 2021.Podemos concluir definiendo una hipótesis de que las ventas han crecido de forma homogénea en todos los distribuidores y que la marca está teniendo un mayor volumen de ventas en el sector. Por lo tanto sería objeto de análisis el estudio de los datos del sector y el impacto en las campañas de marketing que ha tenido la empresa para poder dar una explicación a este aumento en ventas.


3. Análisis de los distribuidores

El objetivo de analizar los distribuidores trata de detectar cuales son los que más cifra de ventas proporcionan a la empresa y a su vez la rentabilidad de vender en cada uno de ellos. Para ello analizamos los gráficos 2 y 3 donde vemos las distribución del total de ventas, el beneficio operativo y el margen operativo para cada distribuidor.

![image](https://github.com/user-attachments/assets/f3f44111-888d-48c5-a02c-63d3e4a8959e)


Analizando las ventas detectamos que West gear es la compañía donde más se consigue materializar las ventas con un volumen de 242M$, seguido por Foot Locker (220M$) y Sports Direct (182M$). Estos tres distribuidores también son con los que más beneficio operativo obtiene la compañía. Analizando el margen operativo detectamos una gran diferencia en el margen que se obtiene en el distribuidor Sports direct. En este se consigue un margen del 41% en ventas mientras que en el resto oscila entre el 37% y el 35%. Debido a esto surge la oportunidad de definir una estrategia para aumentar el volumen de ventas en este canal ya que es el más rentable.

4. Análisis de los productos
5. 
El objetivo del análisis de lso productos tene un enfoque similar al análisis de los distribuidores y trata de detectar cuales son los productos con los que la empresa logra una mayor facturación y cuáles son más rentables para la empresa. Para ello se analizan los gráficos 4, 6 y 7; Distribución de unidades vendidas, de ventas, beneficio operativo y margen operativo.

![image](https://github.com/user-attachments/assets/1da6b3be-5249-445c-b444-3578667b617c) ![image](https://github.com/user-attachments/assets/0e3e91e8-6bf0-4628-a580-4ec544db3229)


El estudio de estos gráficos muestra que la venta de los productos se reparte de forma porcentual entre un 24% en calzado casual masculino y un 12% en 





  
  
