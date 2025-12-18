# **Challenger de Análisis de Datos sobre las ventas realizado de Cuatro Tiendas**

## **Descripción**

Este proyecto realiza un análisis de datos de ventas de cuatro tiendas con el objetivo de identificar tendencias, patrones y obtener insights relevantes para la toma decisiones que ayudaran al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. El objetivo es identificar la tienda menos eficiente y presentar una recomendación final basada en los datos.

## **Dataframes con la información de las cuatro tiendas**

### 1. Importar la información de las cuatro tiendas:
       Se importaron de los archivos CSV desde una URL de un repositorio de Git de la siguiente manera:
```
#### import pandas as pd

url1 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv"
url2 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv"
url3 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv"
url4 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv"

tienda1 = pd.read_csv(url1)
tienda2 = pd.read_csv(url2)
tienda3 = pd.read_csv(url3)
tienda4 = pd.read_csv(url4)

tienda1.sample(10)
tienda2.sample(10)
tienda3.sample(10)
tienda4.sample(10)

```
### 2. Detalle de los Datos importados  

Cada archivo CSV contiene la siguiente información sobre las ventas de cada una de las tiendas:

* Fecha de la venta
* Producto
* Categoría del producto
* Precio
* Cantidad vendida
* Costo de envío
* Calificación del cliente

## **Dependencias instalas de Python**

* pandas
* matplotlib


## **Análisis de factibilidad en el siguiente orden:**

a)	Análisis de facturación: Consiste en calcular el ingreso total de cada tienda. Sumando los valores de la columna Precio de cada conjunto de datos de la tienda para estimar los ingresos.

b)	Ventas por categoría: El objetivo es calcular la cantidad de productos vendidos por categoría en cada tienda. La idea es agrupar los datos por categoría y contar el número de ventas de cada tipo, mostrando las categorías más populares de cada tienda.

c)	Calificación promedio de la tienda: Se debe calcular las calificaciones promedio de los clientes para cada tienda. El objetivo es conocer la satisfacción del cliente con los productos vendidos.

d)	Productos más y menos vendidos: Es necesario identificar qué productos fueron los más vendidos y los menos vendidos en cada tienda. 

e)	Envío promedio por tienda: En este caso vamos a calcular el costo de envío promedio para cada tienda. El objetivo es comprender cuánto se gasta, en promedio, en el envío de cada tienda.

##  **Resultados**

El análisis proporciona información detallada acerca de:

*  La facturación total de cada tienda.
*  Las ventas por categoría de producto en cada tienda.
*  La calificación promedio de satisfacción del cliente por tienda.
*  Los productos más y menos vendidos en cada tienda.
*  El costo de envío promedio por tienda.

## **Conclusiones**

Se realizó un informe que resume cada uno de los resultados obtenidos en el análisis, concluyendo que la tienda con menor rendimiento, que debería venderse seria la tienda 4 y sobre este reporte se realizaria la recomendación al propietario de las tiendas.


## **Contacto**

[Alura LATAM-ORACLE] 
