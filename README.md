# springboot-jwt-demo

# 🌱 Spring Boot JWT Authentication Demo

This project is a **learning setup** I built to understand how **Spring Security + JWT (JSON Web Tokens)** work together in a Spring Boot application.  
It covers the end-to-end flow of authentication, authorization, and securing REST APIs with roles.

---

## 🚀 Features Implemented
- User authentication using **JWT tokens** (`/signin` endpoint).  
- Role-based authorization with `@PreAuthorize` annotations:
  - `/user` → accessible to role `USER`
  - `/admin` → accessible to role `ADMIN`
- In-memory user storage with different roles (`USER`, `ADMIN`).  
- Stateless authentication using `SecurityContextHolder`.  
- Custom exception handling for unauthorized access.  
- JWT filter integrated into the Spring Security filter chain.

---

## 🛠️ Tech Stack
- **Spring Boot 3**  
- **Spring Security 6**  
- **JWT (jjwt library)**  
- **Maven**  
- **Java 24**  

---
## 🔑 Default Users
For simplicity, I used **in-memory users** with different roles:

| Username | Password     | Role  |
|----------|-------------|-------|
| `user`   | `userPassword`   | USER |
| `admin`  | `adminPassword`  | ADMIN |

## ✨ What I Learned
- How Spring Security authenticates requests.
- How JWT tokens are generated, validated, and used in requests.

---
