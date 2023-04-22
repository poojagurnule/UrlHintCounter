<h1 align = "center"> URL HIT COUNTER PROJECT</h1>

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
This project is a UrlHitCounter built using Spring Boot with Java.

---

## Framework Used
* Spring Boot

---

## Language Used
* Java

---

## Data Flow

In this project, we have two layers-
* **Controller** - The controller layer handles the HTTP requests, translates the JSON parameter to object, and authenticates the request and transfer it to the business (service) layer. In short, it consists of views i.e., frontend part.
* **Service** -The business layer handles all the business logic. It consists of service classes and uses services provided by data access layers.se respectively.
You can customize the business logic for updating and retrieving the hit count based on your requirements. For example, you can use a database or an external cache to store and retrieve the hit count.

---

## Data structure Used
* Hashmap
```
We have used HashMap data structure to implement UrlHitCounter .
```
---

## Project Summary

The above project implements a simple URL hit counter feature using Spring Boot. It consists of a UrlHitController class that handles the URL hit count endpoint and calls the UrlHitService class to handle the business logic. The UrlHitService class maintains a hit count and provides methods to update and retrieve the hit count. The application can be tested locally by running the Spring Boot application and accessing the hit count endpoint. The implementation can be customized further based on requirements, such as associating hit counts with specific usernames

## Author

👤 **Pooja Gurnule**

* GitHub: [Pooja Gurnule](https://github.com/poojagurnule)

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page]("url").

---

## Show your support

Give a ⭐️ if this project helped you!

---

.
