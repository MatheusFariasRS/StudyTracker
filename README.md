# Study Tracker

[![License](https://img.shields.io/npm/l/react)](https://github.com/MatheusFariasRS/StudyTracker/blob/main/LICENSE)

## Sobre o projeto

StudyTracker é uma aplicação full-stack para organização de estudos, permitindo criar matérias (subjects), tópicos e subdivisões menores de maneira visual, clara e produtiva.
O objetivo é facilitar o planejamento e o acompanhamento da evolução do usuário ao longo do tempo.

---

## Tecnologias utilizadas

### Back end

- Java 17
- Spring Boot
- Spring Data JPA / Hibernate
- Maven

### Front end

- ReactJS com TypeScript
- HTML / CSS / JavaScript

### Banco de dados

- PostgreSQL

### Contêineres e implantação

- Docker
- Docker Compose (orquestração dos containers)

---

## Como executar o projeto

### Pré-requisitos

- Java 17 instalado
- Node.js + npm ou yarn instalados
- Docker e Docker Compose instalados (para execução via containers)

---

## Executando localmente sem Docker

### Back end

```bash
# Clonar o repositório
git clone https://github.com/MatheusFariasRS/StudyTracker.git

# Entrar na pasta do back end
cd StudyTracker/backend

# Executar o projeto
./mvnw spring-boot:run
```

### Front end

```bash
# Entrar na pasta do front end
cd StudyTracker/frontend

# Instalar dependências
yarn install   # ou npm install

# Executar o projeto
yarn start     # ou npm run start
```

---

## Executando com Docker

> Observação: o arquivo `docker-compose.yml` será configurado durante a implementação da pasta `/infrastructure`.

```bash
# Clonar o repositório
git clone https://github.com/MatheusFariasRS/StudyTracker.git

# Entrar na pasta raiz do projeto
cd StudyTracker

# Subir os containers (back end, front end e banco)
docker-compose up --build
```

---

## Estrutura do projeto

```
/backend         → Aplicação Spring Boot
/frontend        → Aplicação React + TypeScript
/infrastructure  → Configurações de Docker, docker-compose.yml, .env, etc.
/docs            → Documentação geral do projeto (arquitetura, modelo ER, etc.)
README.md
LICENSE
```

## Autor

**Matheus Aguiar Farias**
[LinkedIn](https://www.linkedin.com/in/matheus-farias-3588621b0/)
