
# Instalación
## Instalar paquete de Typescript
```bash
npm i typescript -D
```
## Instalar paquetes de configuración de Typescript
```bash
npx tsc --init
```
## Instalar paquete de Express.js
```bash
npm i express
```
## Instalar paquetes de Express.js para Typescript
```bash
npm i -D @types/express
```
## Instalar nodemon
```bash
npm i -D nodemon
```
## Instalar interprete de nodemon para Typescript
```bash
npm i -D ts-node
```

# Configuración
## Configurar Typescript
Modificar la configuración del archivo tsconfig.json de la siguiente manera
```json
{
    "rootDir": "./src",
    "outDir": "./build",
    "noImplicitAny": true,
    "strictNullChecks": true,
    "strictFunctionTypes": true,
}
```
## Configurar scripts de Node.js
Modificar el archivo package.json
```json
"scripts": {
    "start": "node ./build/index.js"
},
```
# Generar build
```bash
npx tsc
```
