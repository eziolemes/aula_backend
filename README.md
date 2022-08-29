# aula backend NodeJS

npm start -p: criar package.json sem ter que preencher dados
node src/soma.js: executar um arquivo específico

tsc node/sum.ts: vai gerar um arquivo sum.js e pode executar este arquivo
tsc --init: criar um arquivo de configuração (tsconfig.json) para deixar a aplicação rodando

no arquivo tsconfig.json:
    descomenta a linha do comando outDir e informe um diretório para onde vai ser criar os arquivo js convertidos e roda o comando tsc para pegar os arquivos ts e converter para js

tsc -w: executar projeto com ts
-------------------------------------------------------------------
yarn add typescript ts-node-dev @types/express -D
yarn tsc --init: transpilar para js usando o ts do projeto e não o global

nodemoon: para fazer autoreload
yarn add dotenv: adicionar um gerenciador de variaveis de ambiente .env
yarn add reflect-metadata --save
