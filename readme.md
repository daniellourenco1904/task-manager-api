# Task Manager API

API REST desenvolvida em Java e Spring Boot para gerenciamento de tarefas.

## Tecnologias

- Java 21
- Spring Boot
- Spring Data JPA
- H2
- Maven

## Funcionalidades

- Criar tarefas
- Listar tarefas
- Buscar tarefas por ID
- Atualizar tarefas
- Excluir tarefas
- Marcar tarefas como concluídas

## Padrões utilizados

### Repository Pattern

Utilizado através do Spring Data JPA para abstrair o acesso aos dados.

### Service Layer

A camada de serviço concentra as regras de negócio e evita que o Controller acesse diretamente o banco de dados.

### MVC

O projeto separa Controller, Service e Model, facilitando manutenção e organização.

## Como executar

mvn spring-boot:run

A API estará disponível em:

http://localhost:8080