![Static Badge](https://img.shields.io/badge/React-blue?logo=REACT)
![Static Badge](https://img.shields.io/badge/Type%20Script-black?logo=typescript)

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)


Este repositório contém o projeto desenvolvido durante a semana DevSuperior SDS3 ministrado pelo
professor [Nelio Alves](https://www.udemy.com/user/nelio-alves/), oferecido pela plataforma [DevSuperior](https://devsuperior.com.br/).</br></br>
Este projeto visa criar um WebSite DSVENDAS que exibe um relatório com as vendas realizadas por vendedor demonstrado também com gráfico.
Usando tecnologias **Java, Spring Boot, Spring Data JPA, React, Type Script**.</br>

## Modelo conceitual

![image](https://github.com/Sammy192/projeto-SDS3/assets/53224915/0ed142e8-cf1a-4113-ac04-c6402c0c69f4)


## Layout

![image](https://github.com/Sammy192/projeto-SDS3/assets/53224915/92e12850-2409-405c-8881-0121e5d31e33)

![image](https://github.com/Sammy192/projeto-SDS3/assets/53224915/405615f7-4caf-4f19-9e49-b26a100d4d9a)

## Como executar este projeto

IDEs utilizadas normalmente:
- **Java 17**: [JDK 17](https://www.oracle.com/java/technologies/downloads/) ou superior.
- **IDEs**: [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) ou [Spring Tools](https://spring.io/tools).
- **VsCode** para o front-end

Realizar o download ou clone do repositório.
Para executar o back-end:
Importe a pasta 'backend' na sua IDE de preferência e execute a classe principal do projeto.

Para executar o front-end:
Importe a pasta 'front-end' na sua IDE de preferência.
Execute o comando:
```
npm install
após executar
yarn start
```
Aguarde o projeto ser carregado no seu navegador.

## Endpoints da API:
Download coleção do postman -> https://drive.google.com/file/d/1fNtgZ_zBgpKaCGFfWpBNzLX6PtRJ_Puy/view?usp=sharing
Pode ser importado os endpoints no postman

```

GET /sellers - Retorna lista de vendedores.

GET /sales?page=1&sort=date,desc - Retorna a lista de vendas paginada com opção de filtros

GET /sales/amount-by-seller - Retorna a lista de total de vendas para cada vendedor.

GET /sales/success-by-seller - Retorna detalhes de cada vendedor.

```

