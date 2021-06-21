# Base React Projects

## Generalidades del proyecto

Este proyecto explica como configurar los proyectos con React en forma manual, creando una estructura base para clonar y usar posteriormente en otros proyectos.

## En progreso... :construction:

## Requerimientos

El equipo debe tener instalado Nodejs, npm y/o yarn (para MacOS).

## Pasos Generales crear proyecto en local

* Crear directorio (mkdir)
`$ mkdir <nombre-projecto>`

* Ingresar al directorio creado
`$ cd <nombre-projecto>`

* Iniciar un repositorio git para manejar el versionamiento.
`$ git init`

* Inicializar el proyecto (la opción -y otorga una preconfiguración que puede ser modificada posteriormente en el archivo package.json)
`$ npm install -y`

* Organizar la estructura del proyecto, creando los directorios y archivos escenciales.

  ```sh
  ├── README.md
  ├── package.json
  ├── package-lock.json
  ├── .gitignore
  ├── public
  │   ├── index.html
  └── src
      ├── components
      └── index.js
  ```


# Autor

La documentación ha sido creada por Jenny Aguilar, alias jaguilarweb.