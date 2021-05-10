# DSVendas 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/pedrocgrj/projeto-sds3/blob/master/LICENSE) 

# Sobre o projeto

https://pedrocgrj-dsvendas.netlify.app/

DSVendas é uma aplicação full stack web construída durante a 3ª edição da **Semana DevSuperior** (#sds3), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

Esta aplicação consiste em exibir dados fornecidos por um back end construído com Spring Boot, que também apresenta um dashboard com gráficos baseados nestes dados.

## Layout Inicial
![Pagina Inicial 1](https://github.com/pedrocgrj/assets/blob/main/SemanaDevSuperior3/principal.PNG) 

## Layout Dashboard
![Dashboard](https://github.com/pedrocgrj/assets/blob/main/SemanaDevSuperior3/Dashboard.PNG)

## Modelo conceitual
![Modelo Conceitual](https://github.com/pedrocgrj/assets/blob/main/SemanaDevSuperior3/Modelo%20conceitual.PNG)

# Tecnologias utilizadas
## Back end
- JPA
- H2
- Postgres
- Security
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Apex Charts
- Expo
## React
- Três pilares do React
  - Componentes
  - Props
  - Estado
- React Hooks
  - useState
  - useEffect
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/pedrocgrj/projeto-sds3

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto front end web
cd frontend

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Pedro Henrique Ribeiro Fernandes

https://www.linkedin.com/in/pedro-henrique-ribeiro-fernandes-4250907b/
