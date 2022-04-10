
# Práctica 1: Web scraping

## Noticias CNN: Pandemia por COVID-19

### Equipo

Author: Diego Octavio Labastida Tolalpa
Esta práctica es realizada de manera individual.

### Descripción

Práctica _Web Scraping_ que extrae de la página web de CNN en Español (https://cnnespanol.cnn.com) las noticias por un tema dado.
El tema seleccionado para este ejercicio es la enfermedad **COVID-19**, ya que hoy en día es de alto interes para la sociedad.

### Información Extraida

- Clave
- Título
- Autor
- Titulo Busqueda
- Etiqueta
- Fecha
- Hora
- Titulo Imagen
- Imagen URL
- Noticia URL
- Contenido

**Nota:** Este proyecto puede ser modificado para extraer información de otrops temas de interes de la página https://cnnespanol.cnn.com

### Archivo robots.txt

    Sitemap: https://cnnespanol.cnn.com/sitemap_index.xml
    Sitemap: https://cnnespanol.cnn.com/news-sitemap.xml
    
    User-agent: *
    Disallow: /wp-admin/
    Allow: /wp-admin/admin-ajax.php

Permite el acceso a cuañquier robot y solo excluye el directorio _/wp-admin/_ aunque dentro de este tenemos permitido acceder a _/wp-admin/admin-ajax.php_