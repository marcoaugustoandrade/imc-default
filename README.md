# IMC

## Criando o projeto Nodejs
npm init -y

## Instalando as dependências
npm install --save-dev @babel/cli
npm install --save-dev @babel/core
npm install --save-dev @babel/present-env

## Editando o arquivo package.json
"scripts": {
  "build": "babel src/assets/js -d dist/assets/js --source-maps",
  "watch": "babel src/assets/js -d dist/assets/js --source-maps --watch"
}

## Editando o arquivo .babelrc


## Instalando o linter
sudo npm install -g eslint

## Inicializando o ESlint no projeto
eslint --init

Serão realizadas algumas perguntas:
Como você quer utilizar o ESLint? a) Checar somente a sintaxe b) Checar a sintaxe e resolver problemas c) Checar a sintaxe, resolver problemas e forçar um estilo de código

Qual tipo de módulos seu projeto usa? a) JavaScript modules (import/export) b) CommonJS (require/exports) c) Nenhum desses

Qual framework seu projeto usa? a) React b) Vue.js c) Nenhum desses

Onde seu código vai rodar? a) Navegador b) node

Qual o formato do arquivo de configuração? a) JavaScript b) YAML c) JSON

## Rodando o ESLint
eslint src/assets/js/functions.js
eslint src/assets/js/functions.js --fix

## Adicionando regras no .eslintrc.json

## Utilizando estilos populares

## Plugin ESlint


## Automatizando tarefas com o Gulp
