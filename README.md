
# Práctica 1: Web scraping

## Noticias Feminicidio CNN

### Equipo

Author: Diego Octavio Labastida Tolalpa
Esta práctica es realizada de manera individual.

### Descripción

Práctica _Web Scraping_ que extrae de la página web de CNN en Españil (https://cnnespanol.cnn.com) las noticias por un tema dado.
El tema seleccionado para este ejercicio es el **Feminicidio**, ya que hoy en día es de alto interes para la sociedad.

### Información Extraida

- Titulo
- Autor
- Titulo Busqueda
- Etiqueta
- Fecha
- Hora
- Titulo Imagen
- Imagen URL
- Contenido

**Nota:** Este proyecto puede ser modificado para extraer información de otrops temas de interes de la página https://cnnespanol.cnn.com

### Archivo robots.txt

    Sitemap: https://cnnespanol.cnn.com/sitemap_index.xml
    Sitemap: https://cnnespanol.cnn.com/news-sitemap.xml
    
    User-agent: *
    Disallow: /wp-admin/
    Allow: /wp-admin/admin-ajax.php

Permite el acceso a cuañquier robot y solo excluye el directorio _/wp-admin/_ aunque dentro de este tenemos permitido acceder a _/wp-admin/admin-ajax.php_