# Pokédex Spring Boot Application

## Descrição

Este projeto é uma aplicação web simples de Pokédex desenvolvida com Spring Boot. A aplicação serve uma interface frontend estática construída com HTML, CSS e JavaScript, e possui um backend básico com um endpoint de exemplo.

## Estrutura do Projeto

A estrutura do projeto é a seguinte:

demo/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com/
│ │ │ └── example/
│ │ │ └── demo/
│ │ │ ├── controller/
│ │ │ │ └── ApiController.java
│ │ │ └── DemoApplication.java
│ │ └── resources/
│ │ └── static/
│ │ ├── css/
│ │ │ └── style.css
│ │ ├── favicons/
│ │ ├── images/
│ │ │ └── pokedex.png
│ │ ├── js/
│ │ │ └── script.js
│ │ └── index.html
├── pom.xml


## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/pokedex-spring-boot.git
    cd pokedex-spring-boot
    ```

2. Compile e empacote a aplicação:
    ```bash
    mvn clean package
    ```

3. Execute a aplicação:
    ```bash
    mvn spring-boot:run
    ```

4. Abra um navegador e acesse `http://localhost:8080`.

## Dependências

- Spring Boot Web
- Spring Boot Data JPA
- H2 Database

## Funcionalidades

- Interface de Pokédex com busca de Pokémon por nome ou número.
- Navegação entre Pokémon usando botões "Prev" e "Next".

## Autor

Marco Aurélio Kovaleski
