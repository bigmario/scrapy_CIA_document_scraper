# SCRAPER

Este es un proyecto de Scrapy que extrae información de la [Colección de Documentos Historicos de la CIA](https://www.cia.gov/readingroom/historical-collections).
<br>
Este proyecto está diseñado para demostrar cómo usar Scrapy para extraer datos de manera automatizada.

## Requisitos

Este proyecto requiere Python 3 y Scrapy para ejecutarse. Puedes crear el environment e instalar las dependencias con los siguientes comendos:

```
python -m venv venv
source venv/bin/activate
pip install -r requirements
```


## Uso

Para ejecutar la araña en Scrapy, sigue estos pasos:

1. Clona el repositorio en tu computadora.
2. Abre una línea de comando en el directorio del proyecto.
3. Ejecuta los siguiente comandos: 
```
cd bigmario_intelligence_agency
scrapy crawl cia
```

Los datos extraídos se guardarán en un archivo CSV llamado `cia.json` en el directorio de salida (`bigmario_intelligence_agency`).

## Configuración

Puedes configurar la araña de Scrapy en el archivo `settings.py`. Aquí puedes cambiar las configuraciones de Scrapy, como el tiempo de espera y los campos a extraer.

## Contribución

Si deseas contribuir a este proyecto, siéntete libre de crear una pull request. Asegúrate de seguir las directrices de contribución y de explicar tus cambios.