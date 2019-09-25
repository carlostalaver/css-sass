# En este proyecto configuro el ambiente para trabajar con sass
  1 - Trabajando con nodeJs versión v10.16.0
  2 - Trabajando con npm versión 6.10.0

# Para configurar el proyecto:
  1 - npm init -y (Para crear el archivo package.json)
  2 - npm install node-sass [-g]
  3 - En el archivo package.json incluir 
          "scripts": {
            "test": "echo \"Error: no test specified\" && exit 1",
            "sass": "node-sass -w sass / -o css /"
          }

      para compile automaticamente de sass a css.
  
