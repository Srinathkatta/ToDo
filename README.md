<h1 align = "center"> Todo Application </h1>

<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.0.5-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>
This is a simple TODO Application developed using Spring Boot framework, which allows users to manage their tasks in a convenient manner. The application uses an ArrayList as the data structure to store the tasks.

---

## Framework Used
* Spring Boot
---

## Language Used
* Java
---

## Data Model

The Todo data model is defined in the Todo class, which has the following attributes:


* Todo
```
Id: The unique identifier for the Todo.
Name: The name of the Todo.
Status : status of Todo.

```


## Data Flow

1. The user at client side sends a request to the application through the API endpoints.
2. The API receives the request and sends it to the appropriate controller method.
3. The controller method makes a call to the method in service class.
4. The method in service class builds logic and retrieves or modifies data from the database, which is in turn given to controller class
5. The controller method returns a response to the API.
6. The API sends the response back to the user.

---


## Data structure Used
* ArrayList
```
We have used ArrayList data structure as a database to implement CRUD Operations 
```
---

## Project Summary
The Spring Boot TODO Application is a simple task management system that allows users to add, view, mark as complete,
and delete tasks. It utilizes the Spring Boot framework, with an ArrayList serving as the underlying data structure to store the tasks.

## Author

👤 **Srinath Katta**

* GitHub: [Srinath Katta](https://github.com/SrinathKatta)

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page]("url").
    
---

## Show your support

Give a ⭐️ if this project helped you!
    
---
