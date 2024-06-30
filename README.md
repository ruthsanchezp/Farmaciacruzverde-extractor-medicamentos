# Scraper de Cruz Verde

Este proyecto es un spider de Scrapy para extraer información de productos del sitio web de Cruz Verde, específicamente centrado en medicamentos.

## Descripción

El spider navega por las páginas del sitio web de Cruz Verde y extrae la siguiente información para cada producto:

- **Nombre**: El nombre del producto.
- **Precio**: El precio del producto.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/cruzverde-scraper.git
   cd cruzverde-scraper
## Paquetes
1. pip install scrapy
2. Ejecutar scrapy runspider CruzVerdeSpider.py -o productos_cruzverde.json -t json en la terminal
