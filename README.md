<p align="center">
<img width="200" src="https://user-images.githubusercontent.com/106528887/195679263-f22c7d55-4ad4-4d22-9fe5-a4f7e117e534.jpg" alt="logo">
</p>

# **About**

This application is a simplified version of the cinema service. It allows user registration, creating shopping cart, ordering tickets

# **Features**

- register a new user
- implemented the opportunity to add a role to the user
- ADMIN can add movie, movie session
- USER can order ticket
- log in/ log out

# **Project structure**

## The project has 3-Tier Architecture

1. DAO
     - all database work takes place here (CRUD methods)
2. SERVICE
     - all business login takes place here
3. CONTROLLER
     - all communication between the client and the server takes place here

# **Technologies:**

- Java 11
- Spring WEB
- Spring MVC
- Spring Security
- Maven
- Hibernate
- MySQL
- Tomcat

# **What needs to be done to start the project?**

- Fork this repository
- Clone the repository to your PC
- Edit db.properties file - set the necessary parameters:

```
    #MySQL properties
    db.driver=DRIVER
    db.url=URL
    db.user=USERNAME
    db.password=PASSWORD

    #Hibernate properties
    hibernate.show_sql=PROPERTY
    hibernate.hbm2ddl.auto=PROPERTY
    hibernate.dialect=DIALECT
```
- Install [Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)
- Add Tomcat server to configuration
- Run project