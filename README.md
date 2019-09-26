# Sass start
   Iniciando con sass

## Comenzando 🚀

### Pre-requisitos 📋

_Que cosas necesitas para instalar el software y como instalarlas_
  * [Node](https://nodejs.org/es/)        - v10.16.0
  * [Npm](https://www.npmjs.com/get-npm)  - 6.10.0
  * [Sass](https://sass-lang.com/)        - 4.9.0

## Para configurar el proyecto:
  * **npm init -y** (Para crear el archivo package.json)
  *  **npm install** node-sass@4.9.0  [-g]


### En el archivo package.json incluir 
  _Para establecer el guardado automatico_
  ```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "sass": "node-sass -w sass / -o css /"
  }
  ```
  _para compile automaticamente de sass a css._
  
  ## Nota: para solventar el error al guardar automaticamente
  
   _Tuve que usar la versión 4.9.0 de node-sass y reemplazar el archivo render.js por el indicado en este link [git add Render.js](https://github.com/marcosbozzani/node-sass/blob/bug-vscode-watch/lib/render.js)_

  _Para mayor información [aquí](https://github.com/sass/node-sass/issues/1894#issuecomment-390199128)._
    
  
