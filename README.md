# Portfolio con Django 
Más que un portafolio se trata de una práctica en la que tuve que elaborar un sitio web sobre las distintas materias del primer curso de DAW.

Hice el sitio web en python con Django.

La lógica principal consta de categorías en las que hay artículos que hablan sobre una materia. Siendo cada categoría una materia del curso.

Además con el buscador puedes buscar artículos de cualquier categoría.

## Vistas del sitio web:
**Inicio**
![Parte superior de Inicio](img/1.png)
![Parte central](img/2.png)

**Categorías**
![Listado de categorías](img/4.png)


**Artículos**
![Listado de artículos](img/5.png)


**Certificados**
![Certificaciones](img/6.png)


**Contacto**
![Contacto](img/7.png)


**Ejemplo de artículo completo**
![Ejemplo de artículo completo](img/5.png)


**Uso de la búsqueda**
![Uso de la herramienta búsqueda](img/8.png)


## URL del sitio:
https://oscariglsan.pythonanywhere.com


## Muestras del código:

**urls.py**
Archivo donde se especifica que vista, endpoint... etc corresponde a cada url
![urls](img/9.png)


**models.py - ORM de Django**
Especifico que tablas y columnas debe tener la BBDD mediante clases y atributos.
En este caso tengo las clases: Usuario, Categoria y Articulo.
![orm](img/10.png)


**views.py**
![views](img/11.png)


**plantilla: categorías**
![plantilla categorias](img/12.png)


**plantilla: búsqueda**
![plantilla búsqueda](img/13.png)


**settings.py**
En producción la bandera debug debe ser False, e importante incluir la app django en la lista INSTALLED_APPS
![settings](img/14.png)






