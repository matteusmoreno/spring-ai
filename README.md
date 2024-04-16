# Bookstore AI Application

Este é um projeto de demonstração para uma aplicação de assistente de livraria que utiliza a API da OpenAI para responder a perguntas relacionadas a livros e revisões.

## Tecnologias Utilizadas

[![Spring Boot](https://img.shields.io/badge/Spring_Boot-2.6.3-brightgreen)](https://spring.io/projects/spring-boot)
[![OpenAI API](https://img.shields.io/badge/OpenAI_API-0.8.1-blue)](https://openai.com)
[![Java](https://img.shields.io/badge/Java-21-red)](https://www.java.com)
[![Maven](https://img.shields.io/badge/Maven-3.8.5-yellow)](https://maven.apache.org)

## Como Funciona

Esta aplicação é construída usando o Spring Boot e se comunica com a API da OpenAI para fornecer informações sobre livros e revisões. As principais funcionalidades incluem:

- **Consulta de Informações**: Você pode solicitar informações sobre livros best-sellers dos últimos anos através do endpoint `/bookstore/informations`. A aplicação retornará uma resposta com base na pergunta fornecida.

- **Consulta de Revisões**: Você também pode solicitar revisões de livros específicos utilizando o endpoint `/bookstore/reviews`. Basta fornecer o nome do livro como parâmetro e a aplicação retornará um breve resumo do livro e a biografia do autor.

## Como Executar

Para executar esta aplicação, você precisa ter o Java 21 e o Maven 3.8.5 instalados em seu sistema. Siga os passos abaixo:

1. Clone este repositório para o seu ambiente local.
2. Configure sua chave da API da OpenAI no arquivo `application.properties`.
3. Navegue até o diretório raiz do projeto e execute o comando `mvn spring-boot:run`.
4. Após a inicialização, você pode acessar os endpoints da aplicação.

## Endpoints Disponíveis

- **Consulta de Informações**: `GET /bookstore/informations?message={sua_mensagem}`
- **Consulta de Revisões**: `GET /bookstore/reviews?book={nome_do_livro}`

## Contribuição

Sinta-se à vontade para contribuir com melhorias, sugestões ou correções de bugs. Basta abrir uma issue ou enviar um pull request.

