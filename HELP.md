# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/gradle-plugin/reference/html/)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/reference/htmlsingle/#boot-features-jpa-and-spring-data)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/reference/htmlsingle/#production-ready)
* [Spring for RabbitMQ](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/reference/htmlsingle/#boot-features-amqp)

### Guides
The following guides illustrate how to use some features concretely:

* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/)
* [Messaging with RabbitMQ](https://spring.io/guides/gs/messaging-rabbitmq/)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)

### Exercice

```1) Parte 1 
Integração com api http://www.datapoa.com.br/dataset/poatransporte/resource/bc69456c-1fff-4e6f-875b-c3e6d7163c3c, neste site realizar a integração com as operações de linhas de ônibus e itinerário, quando realizar a consulta deve se verificar se a linha já esta cadastrada ou se tem alguma diferença de dados (Linha ou itinerario), caso tenha deve ser atualizada ou caso não tenha deve ser cadastrada no sistema. 
Operações (Integração) 
- Listar as linhas de ônibus - http://www.poatransporte.com.br/php/facades/process.php?a=nc&p=%&t=o 
- Listar itinerário de uma determinada unidade de transporte - http://www.poatransporte.com.br/php/facades/process.php?a=il&p=5566 

2) Parte 2 
Criar Api para ir filtrando as linhas de ônibus por nome. 

3) Parte 3 
Criar um CRUD de cliente, onde consiga cadastrar suas linhas de Ônibus. 

4) Parte 4 
Criar uma operação que faça o filtro de raio de uma determinada unidade de transporte trazendo somente as latitudes que se encaixam nessa busca. Exemplo na request conterá a unidade de transporte a latitude e longitude e o raio que desejo filtrar. 

5) Parte 5 
Criar uma operação que receba uma latitude, longitude e raio, deverá retornar quais unidades de transporte se encontraram nessa faixa de busca. 

6) Documentação da API. 
```