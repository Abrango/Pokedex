# Pokédex Angular

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![codecov](https://codecov.io/gh/keilermora/pokedex-angular/branch/master/graph/badge.svg?token=9E0D28IOFT)](https://codecov.io/gh/keilermora/pokedex-angular)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

[https://keilermora.github.io/pokedex-angular/](https://keilermora.github.io/pokedex-angular/)

La aplicación muestra el listado y el detalle de los Pokémon de las primeras 3 generaciones.

La imagen que representa un Pokémon en el listado muestra las variaciones que estos tuvieron durante las primeras versiones, desde la versión Green (1996) hasta la version Emerald (2005).

Los detalles de un Pokémon individual muestra sus estadísticas base y los registros de la Pokédex de las diferentes versiones.

El proyecto fue desarrollado usando la librería de JavaScript [Angular](https://angular.io/) para crear la interfaz de usuario, en comunicación con la Api RESTful [PokéAPI](https://pokeapi.co/).

## Requisitos mínimos

- [Nodejs](https://nodejs.org) con soporte de largo plazo (LTS).
- Un navegador web

## Ambiente de pruebas

Ejecutar en la raíz del proyecto:

```
npm start
```

## Referencias

- [Angular](https://angular.io/): One framework.
- [Angular Folder Structure](https://angular-folder-structure.readthedocs.io/en/latest/): Create a skeleton structure which is flexible for projects big or small.
- [Font Awesome](https://fontawesome.com/): The web's most popular icon set and toolkit.
- [Normalize.css](https://necolas.github.io/normalize.css/): A modern, HTML5-ready alternative to CSS resets.
- [PokéAPI](https://pokeapi.co/): The RESTful Pokémon API.

# Paso a paso
## Paso 1
### Preparación de la aplicación
Preparación de la aplicación
Nos aseguramos de que la aplicación esté lista para ser desplegada y que funcione correctamente localmente.

## Paso 2
### Accedemos al Portal de Azure e iniciamos sesión en el Portal de Azure, seleccionamos la instancia de App Service y seleccionamos donde se desea implementar la aplicación.
Accedemos al Portal de Azure e iniciamos sesión en el Portal de Azure, seleccionamos la instancia de App Service y seleccionamos donde se desea implementar la aplicación.
Utilizamos las opciones de despliegue del portal para subir la aplicación y confirmamos el despliegue.

## Paso 3
### Accedemos a la configuración de la aplicación en Azure, configuramos los encabezados de seguridad para obtener una calificación A en https://securityheaders.com/ 
Accedemos a la configuración de la aplicación en Azure, configuramos los encabezados de seguridad para obtener una calificación A en https://securityheaders.com/ 

## Paso 4
### Revisamos los encabezados de seguridad una vez que se hayan guardado los cambios, verificamos que los encabezados de seguridad se están aplicando correctamente utilizando la herramienta en línea https://securityheaders.com/.
Revisamos los encabezados de seguridad una vez que se hayan guardado los cambios, verificamos que los encabezados de seguridad se están aplicando correctamente utilizando la herramienta en línea https://securityheaders.com/ .
