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

* Instalar react

`$ npm install react react-dom`

* Configurar el archivo index.js para importar las librerias de react y react-dom, luego usar el método ReactDOM renderizar el contenido en el elemento con la id="app". Asegurarse que en public/index.html exista un elemento con la id="app".

* Instalar Babel, en el entorno de desarrollo, para tener compatibilidad con todos los navegadores.

`$ npm install @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev `

* Crear el archivo .babelrc y agregar los presets instalados.

* Instalar Webpack

`$ npm install webpack webpack-cli html-webpack-plugin html-loader —-save-dev`

* Crear archivo de configuración de Webpack webpack.config.js

# Autor

La documentación ha sido creada por Jenny Aguilar, alias jaguilarweb.