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

## 🛠️ Technologies Used

| Technology                       | Description                           |
|----------------------------------|---------------------------------------|
| Spring Boot `3.5.3`              | Java application framework            |
| Spring Security                  | Authentication and access control     |
| Thymeleaf + Spring Security Extras | For frontend templating and secure views |
| Java `17`                        | Programming language                  |
| Maven                            | Build & dependency management         |

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
