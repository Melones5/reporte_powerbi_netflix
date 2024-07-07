# ❕Resumen de lo que contiene el dataset

Este dataset contiene datos tanto de películas y tv shows disponibles en Netflix.  Cada entrada contiene datos como: tipo (movie, tv show), título, director, país de orígen, fecha que fue añadida, año de publicación, clasificación, duración, y género.

---

# Descripción de las columnas

- **Show_id**: Indica el identificador correspondiente a cada película o TV show.
- **Type**: Indica si la entrada es de tipo película o TV show.
- **Title**: El título de la película o TV show.
- **Director**: El nombre del director de las películas o los TV shows.
- **Country**: país de origen dónde la película o TV show fue producida.
- **Date_added**: Fecha en la cual la película o TV show fue añadida a netflix.
- **Release_year**: año de publicación de la película o TV show. 
- **Rating**: la clasificación a la cual pertenece la película o TV show, que incluye  TV-MA, TV-14, R, PG-13, TV-PG, TV-Y, PG, TV-G, y TV-Y7.
- **Duration**: La duración de las películas o TV show. En el caso de las películas se proporciona el mismo en minutos,  y en el caso de los TV shows se proporciona en temporadas.
- **Listed_in**: hace referencia al género al que pertenece la película o TV show.

---

# Problemas encontrados en el dataset

## Datos sucios / desordenados
- Existencia de 3 entradas con datos duplicados para películas.
- Se formateo toda la columna “date_added” a tipo fecha.
- La columna “duration” tiene un formato de datos incorrecto. Se quitó en todos los elementos “min”, dejando solamente el número correspondiente a los minutos.
## Datos eliminados del dataset original
- Se eliminó la columna “show_id”, debido a que no van a ser objeto de este análisis. 
- Se eliminaron los elementos de TV shows, debido a que no van a ser objeto de este análisis.
- Se quitó en todos los elementos “min” de la columna “duration”, dejando solamente el número correspondiente a los minutos.

--- 

# 🎯Objetivo 

El propósito de este análisis es visualizar a través de un dashboard simple los diferentes KPI (key performance indicator) sólo de las películas,  que fueron lanzadas desde 1942 a 2021. Tanto de manera general, como en específico del país Argentina.

### Según el set de datos se me ocurrió determinar:
- Total de películas en número.
- Cantidad de directores.
- Cantidad de países.
- Cantidad de categorías.
- Top 5 directores con más películas publicadas.
- Top 5 años con mayor cantidad de películas publicadas.
- Total de películas por clasificación.

### Relevamiento en la segunda hoja del Power BI orientado a Argentina:
- Total de películas en número de Argentina.
- Cantidad de directores en Argentina.
- Cantidad de películas por categoría en Argentina.
- Top 5 directores en Argentina.
- Top 5 categorías en Argentina.
- Total de películas por clasificación.
- Top 5 años con mayor cantidad de películas publicadas.

# 🧾Resultado

El Dashboard interactivo, le permite a cualquier usuario utilizar los diferentes filtros y gráficos para obtener información específica y adecuada sobre el dataset en cuestión.

# 📅Duración del proyecto

El proceso de análisis, limpieza y transformación de los datos tomó un total de 1 semana. El proceso de elaboración del dashboard interactivo con sus respectivos KPI's un total de 1,5 semanas.

---

# 📷Visualizaciones

## Índice

![alt text](/images/image.png)

## Dashboard General

![alt text](/images/image-1.png)

## Dashboard Argentina - 1

![alt text](/images/image-2.png)

## Dashboard Argentina - 2

![alt text](/images/image-3.png)

---

# 👽Tecnologías utilizadas
- **Excel** - Para el análisis preliminar de los datos. 
- **Power BI** - Para la limpieza y transformación efectiva de los datos a utilizar.
- **DAX** (Data Analysis Expressions) - Para la creación de medidas personalizadas.
- **Figma** - Para el diseño UI