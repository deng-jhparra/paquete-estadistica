# Proyecto Paquetes
## Pasos para crear una aplicacion en Node

## Publicar un paquete

##

npm init -y
npm install chart.js canvas chartjs-node-canvas
###


# Documentacion
* https://docs.github.com/en/actions/sharing-automations/creating-actions/creating-a-javascript-action


# En un proyecto nuevo de node 

## copiar esto otra vez

npm install @deng-jhparra/paquete-estadistica-cf@1.0.2

## esta en la ruta 
https://github.com/deng-jhparra/paquete-estadistica-cf/pkgs/npm/paquete-estadistica-cf


# Contenido en .npmrc

registry=https://registry.npmjs.org/
@deng-jhparra:registry=https://npm.pkg.github.com/
//npm.pkg.github.com/:_authToken=""
#${secrets.GITHUB_TOKEN}

# Buscar un paquete 

npm search @deng-jhparra/paquete-estadistica-cf@1.0.5

# Instalar un paquete

npm install @deng-jhparra/paquete-estadistica-cf@1.0.5

# Para corregir y luego hacer merge
git checkout -b corregir
git add .
git commit -m "Your commit message"
git pull origin corregir

## Nuevo

# Error

# Si hay una violacion de alguna politica en github, se debe nuevemente crear el tocken
# rEVISANDO EL YML