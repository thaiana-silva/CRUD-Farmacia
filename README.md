
![Banner Proj Farmacia](https://github.com/thaiana-silva/Ola-Mundo/assets/71598210/64953cd1-fda9-4877-8ed3-431106adf2cb)


# Projeto Farmácia 💊🏪
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

Este projeto fez parte da avaliação final do Bloco II do **Bootcamp Desenvolvedor FullStack Java React da Generation Brasil**. Ele consiste na construção do Backend para uma Farmácia, com a capacidade de manipular os dados dos Produtos. Os produtos estão classificados por categorias, permitindo uma gestão simples e eficaz.

## 🛠 Funcionalidades

Projeto desenvolvido em **Java** utilizando os conceitos de Programação Orientada a Objetos (POO), Banco de Dados **MySQL** e o framework **Spring Boot**.

#### CRUD de Categoria:

- Criar Categoria;

- Buscar Categoria por ID;

- Buscar Categoria por Nome;

- Listar Todas as Categorias;

- Atualizar Categoria;

- Excluir Categoria.
  

#### CRUD de Produto:

- Criar Produto;

- Buscar Produto por ID;

- Buscar Produto por Nome;

- Listar Todos os Produtos;

- Atualizar Produto;

- Excluir Produto;

- Buscar Produtos por Categoria.


### 👤 ↔️  👥 Relacionamento One to Many
As classes **Categoria** e **Produto** possuem um relacionamento do tipo **One to Many**, ou um-para-muitos. Nesse tipo de relacionamento, uma instância da classe Categoria pode estar associada a várias instâncias da classe Produto, mas cada instância da classe Produto está associada a apenas uma instância da classe Categoria.


## ✅ Boas Práticas 

A estrutura do projeto segue as convenções do Spring Boot, com pacotes distintos para **modelos**, **repositórios** e **controladores**.
As classes estão organizadas de maneira lógica e fácil de entender, facilitando a manutenção.
## 📋 Testes
A API foi testada utilizando o **Insomnia**, garantindo que todas as funcionalidades foram implementadas corretamente e que a aplicação responde de acordo com as especificações.


## ▶️ Executando o Projeto

Clone o projeto

```bash
  git clone https://github.com/thaiana-silva/CRUD-Farmacia
```
Configure o banco de dados no arquivo application.properties.

```bash
spring.datasource.url=jdbc:mysql://localhost/db_seu-banco-de-dados?createDatabaseIfNotExist=true&serverTimezone=America/Sao_Paulo&useSSl=false
spring.datasource.username=seu-username
spring.datasource.password=sua-senha
```

Execute a aplicação Spring Boot.

```bash
  Run AS 🡪 Spring Boot App 
```

Utilize o Insomnia para testar a API.

```bash
  https://app.insomnia.rest/app/dashboard/
```

