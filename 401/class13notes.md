# [Class 13 Reading Notes](https://github.com/snur206/reading-notes/blob/main/401/class13notes.md)

This topic matters because it is a continuation of Spring, but regarding relationship in Spring Data REST and testing. 

## Related data in Spring (only read section “3. One-to-Many Relationship”)

It is a tutorial on the relationships between entities in Spring Data REST. 

Relationships: 

- The Data Model: Library and Address are two entity classes that have one-to-one relationship by using the @OneToOne annotation.

- One-to-Many Relationship: Use @OneToMany and @ManyToOne annotations to define the one to many relationship, also can add the optional @RestResource annotation to customize the association.

- Many-to-Many Relationship: Use @ManyToMany annotation, to which we can also add @RestResource to define many-to-many relationship.

## Baeldung: Spring Integration Testing

Learning to leverage the Spring MVC test framework to write and run tests that test controllers without explicitly starting a Servlet container. WebApplicationContext provides a web application configuration, loading all the application beans and controllers into the context. MockMvc provides support for Spring MVC testing, summarizes all web application beans and makes them available for testing. The reading demostrated how to do some Spring tests.

## Things I want to know more about

How to test.
