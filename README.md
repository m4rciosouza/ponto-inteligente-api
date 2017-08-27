[![Build Status](https://travis-ci.org/m4rciosouza/ponto-inteligente-api.svg?branch=master)](https://travis-ci.org/m4rciosouza/ponto-inteligente-api)
# Ponto Inteligente
API do sistema de ponto inteligente com Java e Spring Boot.
### Detalhes da API RESTful
A API RESTful de Ponto Inteligente contém as seguintes características:  
* Projeto criado com Spring Boot e Java 8
* Banco de dados MySQL com JPA e Spring Data JPA
* Autenticação e autorização com Spring Security e tokens JWT (JSON Web Token)
* Migração de banco de dados com Flyway
* Testes unitários e de integração com JUnit e Mockito
* Caching com EhCache
* Integração contínua com TravisCI
### Como executar a aplicação
Certifique-se de ter o Maven instalado e adicionado ao PATH de seu sistema operacional, assim como o Git.
```
git clone https://github.com/m4rciosouza/ponto-inteligente-api.git
cd ponto-inteligente-api
mvn spring-boot:run
Acesse os endpoints através da url http://localhost:8080
```
### Importando o projeto no Eclipse ou STS
No terminal, execute a seguinte operação:
```
mvn eclipse:eclipse
```
No Eclipse/STS, importe o projeto como projeto Maven.
