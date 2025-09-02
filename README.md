# TakeOut Porject

## 1. Introduction

a dual-platform solution with a management backend for restaurant staff (menu, orders, employees, analytics, voice alerts) and a consumer mini-app for browsing, ordering, payment, and reminders.

## 2. Function Framework

<img width="488" height="488" alt="image" src="https://github.com/user-attachments/assets/d695c682-6ce3-417e-bc5c-5f8b7ac38721" />

### (1) Management-Side Features

Employee Login / Logout, Employee Information Management, Category Management,  Dish Management, Set Meal Management, Dish Flavor / Specification Management,  Order Management, Data Analytics / Reporting, Real-Time Order Notifications.

### (2) User-Side Features

WeChat Authentication (Login), Recipient Address Management, Order History Retrieval,  Dish Specification Viewing, Shopping Cart Functionality, Order Placement,  Online Payment, Category & Menu Browsing.

## 3. Technology Selection
<img width="488" height="488" alt="image" src="https://github.com/user-attachments/assets/f76eeebc-cc32-4113-8214-8ef0330c0459" />

### (1). User Layer

In the system management console front-end, we use technologies such as **HTML5**, **Vue.js**, **ElementUI**, and **Apache ECharts** (for data visualization).  
For the mobile application, we leverage **WeChat Mini Programs**.

### (2). Gateway Layer

**Nginx** is a high-performance HTTP server, primarily used to serve static resources.  
It also plays two critical roles: **reverse proxy** and **load balancing**.  
For example, when deploying the project, we can use **Nginx** to achieve **Tomcat load balancing**.

### (3). Application Layer

- **Spring Boot**: Rapidly builds Spring applications with a *convention over configuration* approach, simplifying setup and development.  
- **Spring MVC**: A module of the Spring framework that integrates seamlessly with Spring without requiring an additional integration layer.  
- **Spring Task**: Spring’s scheduling framework for cron jobs and periodic tasks.  
- **HttpClient**: Library for sending HTTP requests.  
- **Spring Cache**: Spring’s caching abstraction for improving data access performance.  
- **JWT**: JSON Web Token, used for authentication and authorization.  
- **Alibaba Cloud OSS**: Object Storage Service, used for storing files such as images.  
- **Swagger**: Automatically generates API documentation and provides interactive API testing.  
- **Apache POI**: Encapsulates common operations on Excel spreadsheets.  
- **WebSocket**: A real-time communication protocol enabling efficient bidirectional data exchange between client and server, used for order notifications and reminders.

### (4). Data Layer

- **MySQL**: Relational database for core business data storage.  
- **Redis**: In-memory key-value store, often used for caching due to its high performance.  
- **MyBatis**: Persistence framework for database operations.  
- **PageHelper**: MyBatis pagination plugin.  
- **Spring Data Redis**: Simplifies Java code for interacting with Redis.

### (5). Tools

- **Git**: Version control system, used to manage source code in collaborative development.  
- **Maven**: Build and dependency management tool.  
- **JUnit**: Unit testing framework to validate functionality after development.  
- **Postman**: API testing tool that simulates various HTTP requests and retrieves corresponding responses.

## 4. Development Environment
<img width="488" height="488" alt="image" src="https://github.com/user-attachments/assets/c709fec5-062e-444e-ac66-60df5429a5f8" />

