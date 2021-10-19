# yarn install

# COMPILAR Y EJECUTAR EN NODE:

### compilar: tsc

### ejecutar: node dist/index.js

# COMPILAR Y EJECUTAR EN EL NAVEGADOR:

### compilar:
## yarn build

Borra la carpeta dist, luego copiar los archivos que no son typescript que están en la carpeta public a la carpeta dist (como index.html, archivos css) y por último compila los archivos typescript y el resultado (archivos .js) los guarda en la carpeta dist.

### ejecutar:

## yarn start
Especifica a live-server el directorio en donde está el entry point (index.js)
