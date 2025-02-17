Web Services com Spring Boot e JPA / Hibernate



📌 Descrição

Este projeto é um exemplo de aplicação web utilizando Spring Boot, JPA / Hibernate e um banco de dados H2 para testes. O objetivo é demonstrar boas práticas de desenvolvimento e arquitetura de software para aplicações baseadas em web services REST.

Este projeto foi desenvolvido com base no curso de Java COMPLETO do DevSuperior ministrado pelo Dr. Nelio Alves.

🎯 Objetivos do Projeto

Criar um projeto Spring Boot Java

Implementar um modelo de domínio

Estruturar camadas lógicas: resource, service, repository

Configurar banco de dados de teste (H2)

Povoar o banco de dados

Implementar operações CRUD (Create, Retrieve, Update, Delete)

Tratar exceções corretamente

🛠 Tecnologias Utilizadas

Java 17

Spring Boot

Spring Data JPA

Hibernate

H2 Database

Maven

🏛 Modelo de Domínio

O projeto segue um modelo de domínio estruturado com as seguintes entidades principais:

User (Usuário)

Order (Pedido)

Category (Categoria)

Product (Produto)

OrderItem (Item do Pedido)

Payment (Pagamento)

As entidades possuem relacionamentos entre si, como one-to-many, many-to-many, e one-to-one.

🚀 Funcionalidades Implementadas

Cadastro, listagem, edição e remoção de usuários

Cadastro e listagem de pedidos

Cadastro e listagem de produtos

Relacionamento entre pedidos e produtos

Cálculo de subtotal e total em pedidos

Tratamento de exceções para operações inválidas
