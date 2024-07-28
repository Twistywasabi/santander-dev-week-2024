# Desafio Santander dev week 2024 🚩

Desafio baseado na aula "Publicando Sua API REST na Nuvem Usando Spring Boot 3, Java 17 e Railway".

## Objetivo 📜

Criar uma API REST na Nuvem Usando Spring Boot 3, Java 17 e Railway

## Diagrama de Classes

```mermaid
classDiagram
  class User {
    -String name
    -Account account
    -Feature[] features
    -Card card
    -News[] news
  }

  class Account {
    -String number
    -String agency
    -Number balance
    -Number limit
  }

  class Feature {
    -String icon
    -String description
  }

  class Card {
    -String number
    -Number limit
  }

  class News {
    -String icon
    -String description
  }

  User "1" *-- "1" Account
  User "1" *-- "N" Feature
  User "1" *-- "1" Card
  User "1" *-- "N" News
```

## Tecnologias 👨‍💻

Java version "22.0.1" 2024-04-16

Java(TM) SE Runtime Environment (build 22.0.1+8-16)

Java HotSpot(TM) 64-Bit Server VM (build 22.0.1+8-16, mixed mode, sharing)

JDK Compliance 1.6

Spring:
- Maven
- Spring Boot 3.3.2
- Packaging Jar
- Java 17
- Spring Web
- Spring data JPA
- H2 Database




## Referências 📚

https://github.com/falvojr/santander-dev-week-2023

## Atualizações 🕐

28/07/2024

Adição do projeto no github

## Pendências 🚨

