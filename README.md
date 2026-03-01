# Hotel System

# Hotel System - Projeto de Estudos

Projeto de estudos para construção de um sistema de gerenciamento de hotéis utilizando **Java + Spring Boot + PostgreSQL + Docker + Vue**.

O objetivo é aprender:

* Arquitetura backend
* Spring Boot
* Maven
* Docker
* PostgreSQL
* REST API
* Futuramente CI/CD e Deploy

---

# 1. Stack Utilizada

### Backend

* Java 21
* Spring Boot
* Maven
* JPA / Hibernate

### Banco de Dados

* PostgreSQL
* Docker

### Frontend (futuro)

* Vue.js

### DevOps (futuro)

* Docker
* CI/CD

---

# 2. Estrutura do Projeto

```
hotel-estudos
├── backend
│   └── hotel
├── database
├── docker-compose.yml
├── docs
├── frontend
└── README.md
```

---

# 3. Configuração do Ambiente

## 3.1 Java

```
java -version
```

Versão utilizada:

```
Java 21
```

---

## 3.2 Maven

```
mvn -version
```

Versão utilizada:

```
Maven 3.6.3
```

---

## 3.3 Docker

```
docker --version
```

Versão utilizada:

```
Docker 28
```

---

# 4. Banco de Dados com Docker

O banco PostgreSQL roda em um container Docker.

## Subir o banco

```
docker compose up -d
```

Container criado:

```
hotel-postgres
```

Porta utilizada:

```
5433 -> 5432
```


---

