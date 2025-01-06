# Proyecto_Almacenamiento

## Descripción

El proyecto final está diseñado para extraer, procesar y analizar datos de propiedades inmobiliarias desde un portal web. El objetivo principal es obtener información sobre departamentos y sus respectivos precios, convertir los precios de unidades de fomento (UF) a pesos chilenos utilizando el valor actual de la UF, y almacenar los resultados en un DataFrame para su análisis posterior, utilizando librerias de Webscrapping.

### Funcionalidades
- **Extracción de datos:** Se utiliza **web scraping** para extraer información sobre propiedades (título, dirección, moneda, valor, etc.) desde portalinmobiliario y valoruf.
- **Conversión de valores:** Estandariza los valores a moneda en pesos chilenos (CLP)
- **Uso de api:** Se el uso de API de Google para extraer información georeferencial y locales cercanos
- **Consultas SQL:** Se generan preguntas de interes respecto al DF generado.

## Requisitos

- Todos los requisitos se encuentran definidos en archivo **requirements.txt**
