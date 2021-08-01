## Digital Innovation: Construindo um projeto com arquitetura baseada em microsserviços usando Spring Cloud

Este é um projeto de microsserviços com a tecnologia Spring Cloud. Foram desenvolvidos dois serviços com banco de dados distintos: um para controle de produtos e o outro para gerenciamento de carrinho de compras. O objetivo deste projeto é praticar os principais conceitos e vantagens de uma arquitetura baseada em microserviços, utilizado um Service Discovey (Eureca) para detecção automática de dispositivos e serviços, implementando o Spring Cloud Config para configuração externalizada em um sistema distribuído. Também utilizamos o recurso Spring Actuator do SpringBoot para monitorar e gerenciar a nossa aplicação .

**As tecnologias utilizadas foram:**

- Linguagem Java
- Spring Cloud (Eureka, Gateway, Config)
- Spring Data
- Spring Actuator
- Gerenciador de Repositórios Gradle
- IDE Intellij
- Git
- Postman
- Banco de Dados Elasticsearch
- Banco de Dados Redis

**Como iniciar o projeto:**

Para executar o projeto no terminal, digite o seguinte comando:

```
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/product
```

São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

- Java 11 ou versões superiores.
- Gradle 7.0 ou versões superiores.
- Intellj IDEA Community Edition ou sua IDE favorita.
- Postman
- Banco de Dados Elasticsearch
- Banco de Dados Redis

