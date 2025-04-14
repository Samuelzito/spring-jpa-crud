# 🧾 Spring JPA CRUD

Este projeto é uma aplicação simples desenvolvida em Java utilizando Spring Boot e Spring Data JPA. Ele realiza operações CRUD (Create, Read, Update, Delete) com persistência em banco de dados relacional, sendo ideal para fins didáticos e como base para projetos maiores.

---

## 🚀 Funcionalidades

- ✅ Cadastro de entidades
- 🔎 Listagem de dados
- ✏️ Atualização de registros
- 🗑️ Exclusão de dados
- 💾 Persistência com JPA + Hibernate

---

## 🛠️ Tecnologias utilizadas

- Java 17  
- Spring Boot  
- Spring Data JPA  
- Hibernate  
- Maven  
- H2 Database (padrão) ou PostgreSQL / MySQL  
- IDE: IntelliJ IDEA / Eclipse  

---

## 🗂️ Estrutura do Projeto

spring-jpa-crud/ ├── src/ │ └── main/ │ ├── java/ │ │ └── com.example.crud/ │ │ ├── model/ │ │ ├── repository/ │ │ ├── service/ │ │ └── controller/ │ └── resources/ │ ├── application.properties │ └── data.sql (opcional) ├── pom.xml

yaml
Copiar
Editar

---

## ▶️ Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/Samuelzito/spring-jpa-crud.git
Importe o projeto como Maven Project em sua IDE

Altere o banco de dados no application.properties, se necessário:

properties
Copiar
Editar
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
spring.h2.console.enabled=true
Execute a classe com @SpringBootApplication

Acesse:
http://localhost:8080
e use via Postman, Swagger ou frontend externo

