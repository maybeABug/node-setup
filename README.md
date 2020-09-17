ctrl + shift + v => preview readme

## inicializar git

### \$ git init

## inicializar package

### \$ yarn init -y

## add typescript

### \$ yarn add typescript -D

## criar o tsconfig

### \$ yarn tsc --init

## adicionar o express

### \$ yarn add express

## adicionar os tipos para o express

### \$ yarn add @types/express -D

## adicionar o ts-node-dev

### \$ yarn add ts-node-dev -D

## script de dev

- "dev": "ts-node-dev --respawn --transpile-only --ignore-watch node_modules --no-notify src/server.ts"

## adicionar o tsconfig para que o ts-node-dev entenda os caminhos @

### \$ yarn add tsconfig-paths -D

## adicionar o eslint como dependencia de desenvolvimento

### \$ yarn add eslint -D

## inicializar o eslint

### \$ yarn eslint --init

## copiar e instalar todas as dependencias que o eslint deu

### \$ yarn add -D @typescript-eslint/eslint-plugin@latest eslint-config-airbnb-base@latest eslint-plugin-import@^2.21.2 @typescript-eslint/parser@latest9

## configurar o jest 

### \$ yarn add jest -D 

## adicionar types do jest

### \$ yarn add @types/jest -D

## iniciar o jest 

### \$ yarn jest --init


## adicionando a dependencia que faz o jest funcionar com o ts 

### \$ yarn add ts-jest -D 

## adicionando o babel 

## \$ yarn add -D @babel/cli @babel/core @babel/node @babel/preset-env @babel/preset-typescript babel-plugin-module-resolver