# Sistema de Gestão de Estoque e Requisições de Materiais

API REST desenvolvida em Java com Spring Boot para gerenciamento de estoque e controle de requisições de materiais educacionais.

O sistema permite autenticação via JWT, controle de usuários, gerenciamento de estoque e fluxo de aprovação de requisições, seguindo uma arquitetura em camadas e boas práticas de desenvolvimento.

## Objetivo

O projeto simula um ambiente corporativo onde diferentes usuários podem solicitar materiais disponíveis em estoque, enquanto administradores realizam o gerenciamento completo do sistema.

## Tecnologias

### Backend

- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- JWT
- Maven

### Banco de Dados

- PostgreSQL

### Documentação

- Swagger / OpenAPI

## Funcionalidades

### Autenticação

- Login com JWT
- Cadastro de usuários
- Controle de permissões por perfil

### Estoque

- Cadastro de materiais
- Atualização de materiais
- Exclusão de materiais
- Consulta por categoria
- Consulta de materiais sem estoque

### Requisições

- Criação de requisições
- Aprovação e rejeição
- Histórico
- Consulta por usuário
## Arquitetura

O projeto segue uma arquitetura em camadas, separando responsabilidades entre:

- Controller
- Service
- Repository
- DTO
- Mapper
- Validator
- Security
- Entity


## Autores

- Back End - Otávio C. Borges
- Front End - Roger Aguiar

Observação: Este repositório concentra o desenvolvimento da API REST. O frontend foi desenvolvido em colaboração, sendo de responsabilidade de Roger Aguiar, enquanto toda a implementação do backend foi desenvolvida por Otávio C. Borges.
