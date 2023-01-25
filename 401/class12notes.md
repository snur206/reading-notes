# [Class 12 Reading Notes](https://github.com/snur206/reading-notes/blob/main/401/class12notes.md)

This topic matters because it is a continuation of the spring app.

## Spring guide: Accessing Data with JPA

This reading goes through the process of building an app store and retrieve data in a relational database. The example shows how to store an application storing the Customers POJOs (Plain Old Java Objects) in a memory database.

## Baeldung: Comparing repositories

This reading focuses Spring Data repository interfaces and their functionalities. JpaRepository gives JPA related methods like flushing the persistence context and delete records in a batch and contains full API of CrudRepository and PagingAndSortingRepository due to their inheritance relationship. Full functionality given by JpaRepository, you can use CrudRepository.

Each method in JpaRepository:

- findAll() – get a List of all available entities in database

- findAll(…) – get a List of all available entities and sort them using the provided condition

- save(…) – save an Iterable of entities. Here, we can pass multiple objects to save them in a batch

- flush() – flush all pending task to the database

- saveAndFlush(…) – save the entity and flush changes immediately

- deleteInBatch(…) – delete an Iterable of entities. Here, we can pass multiple objects to delete them in a batch

Aggarwal, S. (2022) Spring Data Repositories compared, Baeldung. Available at: https://www.baeldung.com/spring-data-repositories (Accessed: January 25, 2023). 

## Things I want to know more about

Using the JpaRepository 
