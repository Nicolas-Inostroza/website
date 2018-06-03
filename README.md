# Duckietown Web Page
Esta es la versión 1.0 de la página web de Duckietown Chile

# Cómo Modificar
Para modificar los datos de la página, por favor, seguir los siguientes pasos:

* Clonar el repositorio
* Modificar el/los archivos que se quieran cambiar
* Probar localmente
* Subir los cambios

## Jekyll
Jekyll es un framework para crear páginas estáticas de forma dinámica con una excelente integración con GitHub. Para ver como funciona Jekyll, revisar [https://jekyllrb.com/](https://jekyllrb.com/) para ver todos los detalles,
o leer lo básico de: [front matter](https://jekyllrb.com/docs/frontmatter/) y [crear páginas](https://jekyllrb.com/docs/pages/).

## Capacitaciones
Para agregar nuevas capacitaciones, seguir los siguientes pasos:

* Agregar una carpeta nueva con el año de la capacitación en _\_data/capacitaciones_
* Agregar dos archivos y llenar con la información necesaria (seguir las convenciones dadas por los archivos en _\_data/capacitaciones/2017_)
  * members.yaml
  * trainees.yaml
* Agregar una nueva página con formato _año_.md en la carpeta _capacitaciones_
  * Copiar el contenido de _2017.md_ y modificar el nuevo año donde corresponda

# Issues
Si se encuentran algún problema, falta de información o nuevas ideas, por favor agregarlos al [Issue Tracker](https://github.com/Duckietown-Chile/website/issues). Si quieren trabajar en la página, revisar el Issue Tracker para ver lo que hace falta realizar.

# Credits

[Original Jekyll Template](https://github.com/andrewbanchich/editorial-jekyll-theme)