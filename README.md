# Teste de API Rest do manual  ao CI/CD

Bootcamp 001 - Qualiters-club   

## O que é

Este repósitorio foi criado, durante um exércicio, em um bootcamp de teste de API Rest.

## Tecnológias utilizadas

- Postman
- Node v20.14.0
- Newman v6.1.3
- Newman-htmlextra

## Documenetação

- Doc da API: [Consulte Swagger](https://serverest.dev//#/)

## Como instalar o ambiente

- Primeiro: instale o node do seu computador [Baixe aqui](https://nodejs.org/en/download)

- Segundo: realize a instalação do newman de forma global [Baixe aqui a dependência](https://npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: Realize a instalção da dependência para os relatórios (opcional)[newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```
 ```
npm install -g newman-reporter-htmlextra
```
## Como rodar os teste

### Pelo Postman web ou desktop

- Importe a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo Newman

- Abra seu console de preferência 
- Execute a seguinte linha  de comando para rodar os testes
```
 newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute a seguinte linha  de comando para rodar os testes com relatório
```
 newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```
### Report

Se optar em rodar os teste com report htmlextra é gerado um arquivo html com o resultado dos testes e para verificar as validações pode abrir a pasta **newman** que foi criado no local  em que os arquivos da collection e environment se encontram.

## Entre em contato

Email: paty_rosa1@yahoo.com.br

https://www.linkedin.com/in/patricia-rosa-silva/

