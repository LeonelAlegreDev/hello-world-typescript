
# Hello World con Typescript!
Este proyecto es una guía basica para inicializar una aplicación de backend usando el framework Express.js, programado en Typescript y ejecutado con Node.js
# Instalación
## Instalar paquete de Typescript
```bash
npm i typescript -D
```
## Instalar paquetes de configuración de Typescript
```bash
npx tsc --init
```
## Instalar paquetes de Express.js
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
## Instalar intérprete de Nodemon para Typescript
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
    "start": "node ./build/index.js",
    "build": "tsc --build",
    "dev": "nodemon ./src/index.ts"
},
```
# Generar build
```bash
npx tsc
```
