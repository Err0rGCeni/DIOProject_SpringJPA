# Conhecendo o Projeto Spring Data JPA na Prática

Sejam bem-vindos ao projeto de LAB **Conhecendo o Projeto Spring Data JPA na Prática** oferecido gratuitamente pela plataforma de cursos online [**Digital Innovation One**](https://dio.me/).

## 🎯 Objetivo do Projeto

Ao final deste projeto, o Dev irá conhecer os principais conceitos de mapeamento objeto-relacional (ORM) usando o **Spring Data JPA**. Para isso, uma **API RESTful** será desenvolvida com ênfase na modelagem de suas entidades, no domínio de uma academia de ginástica.

## 🚦 Guia

1. Apresentação do Projeto Base
2. Configuração do banco de dados (SGBD *PostgreSQL*)
3. Aplicando as *annotations*
4. Execução do fluxo back-end: *Controller - Service - Repository*
5. Validação - *Hibernate Validator*
6. Consultas Avançadas - *Derived Query - Native Query*

## 🛠 Tecnologias Utilizadas

- IDE IntelliJ
- Java 11
- Maven
- **Spring Web**
- **Spring Data JPA**
- **PostgreSQL Driver**
- **Hibernate Validator**
- Lombok
- Postman

## [Anotações de Mapeamento](https://strn.com.br/artigos/2018/12/11/todas-as-anota%C3%A7%C3%B5es-do-jpa-anota%C3%A7%C3%B5es-de-mapeamento/)

**@Entity**  
Usada para especificar que a classe anotada atualmente representa um tipo de entidade.

**@Table**  
Usada para especificar a tabela principal da entidade atualmente anotada.

**@Id**  
Especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificado.

**@GeneratedValue**  
Especifica que o valor do identificador de entidade é gerado automaticamente.

**@Column**  
Usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados.

**@JoinColumn**  
Usada para especificar a coluna FOREIGN KEY. Indica que a entidade é a responsável pelo relacionamento.

**@OneToMany**  
Usada para especificar um relacionamento de banco de dados um-para-muitos.

**@OneToOne**  
Usada para especificar um relacionamento de banco de dados um-para-um.

**@ManyToOne**  
Usada para especificar um relacionamento de banco de dados muitos-para-um.

**cascade**  
Realizar operações em cascata só faz sentido em relacionamentos Pai - Filho.

**mappedBy**  
Indica qual é o lado inverso ou não dominante da relação.

## 🔗 Links Úteis

- [Spring Initializr](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.6.1&packaging=jar&jvmVersion=11&groupId=me.dio.academia&artifactId=academia-digital&name=academia-digital&description=Tutorial%20API%20RESTful%20modelando%20sistema%20de%20academia%20de%20gin%C3%A1stica&packageName=me.dio.academia.digital&dependencies=web,data-jpa,postgresql,validation,lombok)
- [Common application properties](https://docs.spring.io/spring-boot/docs/2.0.x/reference/html/common-application-properties.html)
- [Spring Data JPA - Reference Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.repositories)


Disponibilizado com ♥ por [cami-la](https://www.linkedin.com/in/cami-la/ "cami-la").
