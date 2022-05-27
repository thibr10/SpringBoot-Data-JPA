### Projeto Spring Data JPA na Prática

##### Projeto Spring Data JPA na Prática realizado pela plataforma de cursos online Digital Innovation One.

###### 🎯 Objetivo do Projeto

Conhecer os principais conceitos de mapeamento objeto relacional (ORM) usando o Spring Data JPA. Para isso, uma API RESTful será desenvolvida com ênfase na modelagem de suas entidades, no domínio de uma academia de ginástica.

###### 🛑 Pré-requistos

    Fundamentos do Spring Boot
    
    Noções de SQL

###### 🚦 Guia

    Apresentação do Projeto Base
    Configuração do banco de dados (SGBD PostgreSQL)
    Aplicando as annotations
    Execução do fluxo back-end: Controller - Service - Repository
    Validação - Hibernate Validator
    Consultas Avançadas - Derived Query - Native Query

###### 🛠 Tecnologias Utilizadas

    IDE IntelliJ
    Java 18
    Maven
    Spring Web
    Spring Data JPA
    PostgreSQL Driver
    MySQL Driver
    Jersey
    Hibernate Validator
    Lombok
    Postman

###### Anotações de Mapeamento

@Entity Usada para especificar que a classe anotada atualmente representa um tipo de entidade.

@Table Usada para especificar a tabela principal da entidade atualmente anotada.

@Id Especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificado.

@GeneratedValue Especifica que o valor do identificador de entidade é gerado automaticamente.

@Column Usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados.

@JoinColumn Usada para especificar a coluna FOREIGN KEY. Indica que a entidade é a responsável pelo relacionamento.

@OneToMany Usada para especificar um relacionamento de banco de dados um-para-muitos.

@OneToOne Usada para especificar um relacionamento de banco de dados um-para-um.

@ManyToOne Usada para especificar um relacionamento de banco de dados muitos-para-um.

cascade Realizar operações em cascata só faz sentido em relacionamentos Pai - Filho.

mappedBy Indica qual é o lado inverso ou não dominante da relação.

###### 🔗 Links Úteis

[Spring Initializr](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.7.0&packaging=jar&jvmVersion=17&groupId=br.com.DioProjetoJPA&artifactId=spring-boot-com-mysql&name=spring-boot-com-mysql&description=Projeto%20Spring%20Data%20JPA%20na%20Pr%C3%A1tica&packageName=br.com.DioProjetoJPA.spring-boot-com-mysql&dependencies=web,data-jpa,postgresql,validation,lombok,jersey,mysql)

[Common application properties](https://docs.spring.io/spring-boot/docs/2.0.x/reference/html/common-application-properties.html)

[Spring Data JPA - Reference Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.repositories)

[Validation Reference Implementation: Reference Guide](https://docs.jboss.org/hibernate/stable/validator/reference/en-US/html_single/#validator-gettingstarted)

[Docker hub MySQL](https://hub.docker.com/_/mysql)

