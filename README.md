# 🔐 Spring Security - Custom Username & Password

This project demonstrates how to secure a Spring Boot application using **Spring Security** with a **custom username and password**, configured via `application.properties`.

> Ideal for beginners who want to understand how Spring Security integrates with Spring Boot using basic authentication.

---

## 📌 Features

- ✅ Spring Boot project with Spring Security integration
- ✅ Custom credentials via `application.properties`
- ✅ Basic browser login popup (no login page yet)
- ✅ Thymeleaf and Spring Security Thymeleaf extras added
- 🚀 Ready to extend with custom login forms, roles, or database auth

---

## 📦 Dependencies Used

These dependencies are declared in `pom.xml`:

| Dependency                                 | Purpose                                                        |
|--------------------------------------------|----------------------------------------------------------------|
| `spring-boot-starter-security`             | Provides Spring Security features like authentication, filters |
| `spring-boot-starter-web`                  | Enables building RESTful web applications                      |
| `spring-boot-starter-thymeleaf`            | Adds Thymeleaf template engine for frontend                    |
| `thymeleaf-extras-springsecurity6`         | Adds Spring Security tags to Thymeleaf (e.g. `sec:authorize`)  |
| `spring-boot-starter-test`                 | Standard testing support with JUnit, Mockito                   |
| `spring-security-test`                     | Adds testing utilities for Spring Security                     |

---

## 🛠️ Technologies Used

| Technology                       | Description                           |
|----------------------------------|---------------------------------------|
| Spring Boot `3.5.3`              | Java application framework            |
| Spring Security                  | Authentication and access control     |
| Thymeleaf + Spring Security Extras | For frontend templating and secure views |
| Java `17`                        | Programming language                  |
| Maven                            | Build & dependency management         |

---
## ▶️ How to Run

### 🔧 Prerequisites

- Java 17+
- Maven 3.6+

---

## 📂 Project Structure

```plaintext
SpringSecurity1/
├── src/
│   └── main/
│       ├── java/
│       │   └── com.example.SpringSecurity1.demo/
│       │       └── Application.java
│       └── resources/
│           ├── application.properties
│           └── templates/  (optional if using Thymeleaf)
├── pom.xml 


