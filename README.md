# Todo List - Spring Boot

Este projeto é uma aplicação de lista de tarefas (Todo List) desenvolvida com Spring Boot.

## Funcionalidades
- Adicionar, listar, editar e remover tarefas
- Persistência de dados com Spring Data JPA
- Estrutura MVC (Model-View-Controller)

## Requisitos
- Java 17+
- Maven

## Como executar
1. Clone o repositório
2. Execute `mvnw spring-boot:run` ou `mvn spring-boot:run`
3. Acesse `http://localhost:8080`

## Estrutura de Pastas
```
src/main/java/com/camargo/todo/
  ├── controller/    # Controllers REST
  ├── entity/        # Entidades JPA
  ├── repository/    # Repositórios
  ├── service/       # Serviços
src/main/resources/
  ├── application.properties # Configurações
  ├── static/                # Arquivos estáticos
  ├── templates/             # Templates HTML
```

## Autor
- Seu nome

## Licença
Este projeto está sob a licença MIT.
