# [Class 29 Reading Notes](https://github.com/snur206/reading-notes/blob/main/401/class29notes.md)

This topic matters because it is an intro to Room.

## Questions

What database engine is Room wrapped around? Do you think this is a good choice? Why or why not?

Wrapped around SQLite. I believe it is a good choice because it provides some benefits like compile-time verification of SQL queries, convenience annotations that minimize repetitive and error-prone boilerplate code, and streamlined database migration paths. 


Do Rooms have any similarities to JPA?

They both are data persistence library.

Describe a DAO in your own words

DAO(Data Access Object) can be defined an interface or an abstract class. You use it when you use Rooms persistence library to store the app's data. You interact with said stored data by defining the DAO. DAO has methods that provides abstract access to your app's database. 

## Things I want to know more about

More on Room and DAO.
