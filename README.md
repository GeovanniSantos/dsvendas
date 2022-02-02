# ![money](https://github.com/GeovanniSantos/dsvendas/blob/main/assets/money.png) DSVendas

![animation](https://github.com/GeovanniSantos/dsvendas/blob/main/assets/animação.gif)

# Sobre o projeto

https://dsvendas-geovanni.netlify.app

DSVendas é uma aplicação full stack web construída durante a 3ª edição da **Semana DevSuperior**, evento organizado pela [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

A aplicação consiste em uma presentação de informações de vendas, onde os dados são coletados no browser e depois são listados na tabela, além disso, também apresenta um dashboard com gráficos baseados nestes dados.


## Modelo conceitual
![Modelo Conceitual](https://raw.githubusercontent.com/devsuperior/bds-assets/main/sds/sds3-mc.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA
- Maven

## Front end
- HTML / CSS / JS / TypeScript
- Bootstrap
- ReactJS
- Apex Charts

## Implantação em produção
- Back end: Heroku
- Front end: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/GeovanniSantos/dsvendas

# entrar na pasta do projeto back end
cd backend

# executar o projeto usando sts ou no terminal com o comando
mvn spring-boot:run
```

## Front end
Pré-requisitos: node / npm / yarn

```bash
# clonar repositório
git clone https://github.com/GeovanniSantos/dsvendas

# entrar na pasta do projeto front end web
cd frontend

# instalar dependências
npm install / yarn install

# executar o projeto
npm start / yarn start
```

