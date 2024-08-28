# Week 1 Exercise Repository

This repository is a comprehensive collection of exercises and projects that were completed as part of Week 1 in the DN 3.0. The exercises span a variety of topics, including data structures and algorithms (DSA), design patterns, and practical Java applications. Each project is designed to reinforce key concepts and provide hands-on experience in software development.

## Data Structures and Algorithms

A significant portion of this repository focuses on implementing various data structures and algorithms in Java. These exercises are structured around real-world scenarios, such as managing an e-commerce platform, an employee management system, financial forecasting, and more. Each project is designed to explore different aspects of DSA, from searching algorithms like binary and linear search to more complex system management like inventory and library management.

For instance, the `EcommercePlatform` project demonstrates how binary and linear search algorithms can be applied to find products within a catalog. Similarly, the `EmployeeManagementSystem` provides insights into organizing and retrieving employee data efficiently. These exercises not only help in understanding the theoretical aspects of algorithms but also in applying them to practical, everyday programming tasks.

## Design Patterns

The repository also includes several examples of design patterns, which are crucial for writing clean, efficient, and reusable code. Each design pattern is explored through a dedicated project. For example, the `ObserverPatternExample` project simulates a stock market where different observers (like web apps) react to changes in stock prices. The `ProxyPatternExample` and `SingletonPatternExample` demonstrate how to manage object creation and control access to resources in a system.

These design pattern examples are written in a way that emphasizes their practical use cases, making it easier to grasp their significance in software design and architecture. Whether you’re new to design patterns or looking to reinforce your understanding, these examples serve as a solid foundation.
 

# Week 2 Exercise Repository

Welcome to the Week 2 Exercise Repository! This collection of files is part of my coursework, where I delved into both Java-based web development and PL/SQL scripting. The repository is divided into two main sections: a Maven-based Library Management System and a series of PL/SQL scripts.

## Library Management System Projects

In this repository, two versions of a Library Management System project is here. Both versions are developed using Java, but each version reflects different stages of the project, showcasing the evolution of the system.

The more recent version in the `LibraryManagement 9` folder, is built using Spring Boot, a powerful framework that simplifies the development of Java applications. This project manages the basic operations of a library, such as adding new books, retrieving book information, updating details, and removing books. The structure includes a variety of Java files organized into controllers, services, and repositories. Additionally, it utilizes Maven for dependency management, ensuring that all necessary libraries are included and up-to-date. If you're familiar with Java and Spring Boot, this project should be straightforward to understand and run.

The earlier version of the project, located in the `LibraryManagement-8` folder, has a similar purpose but a slightly different structure and implementation. This version might be interesting if you're curious to see how the project has progressed and refined over time.

## PL/SQL Scripts

The second part of this repository is a collection of PL/SQL scripts. These scripts are designed to perform various database operations, demonstrating control structures, cursor handling, error management, and more. They also include practical examples such as stored procedures, triggers, and functions, which are essential for managing and manipulating data within a database. For anyone working with Oracle databases or interested in learning PL/SQL, these scripts provide a valuable resource.

In addition to the scripts, there’s a document (`Week 2_PLSQL.docx`) that provides further explanations and context, making it easier to understand the purpose and usage of each script.


# Week 3 Exercise Repository 

This repository contains multiple Java projects related to Week 3 exercises. Each exercise is located in its respective directory and focuses on different aspects of Java programming, including Spring Boot applications and other related technologies.

- **Ex-1 to Ex-4**: Exercises are on basic setups, configurations, or simpler Java applications demonstrating fundamental concepts.
- **Ex-5**: Employee Management System project focusing on CRUD operations and possibly integrating a database.
- **Ex-6**: Another iteration or enhancement of the Employee Management System.
- **Ex-7 to Ex-10**: Potentially includes advanced topics like auditing, JPA configurations, projections, and other Spring Boot features.

### How to Run

To run any of these:

1. Navigate to the directory of the exercise we wish to run.
2. Should have Java and Maven installed on machine.
3. Use the following Maven command to build and run the project:

   ```sh
   mvn clean install
   mvn spring-boot:run
   ```

4. For exercises that involve tests, you can run the tests using:

   ```sh
   mvn test
   ```

### Prerequisites

- **Java**: Java 8 or above is installed.
- **Maven**: Required to build and manage dependencies.
- **.metadata and `.mvn` directories**: These contain configuration and metadata files for the IDE and Maven wrapper.
- **pom.xml**: The Project Object Model file used by Maven to manage the project's dependencies and build process.
- **HELP.md**: Additional help or documentation specific to a project.


# Week 4 Exercise Repository

Welcome to the **Week 4 Java Exercises** repository. This collection of exercises is designed to deepen the understanding of Java, Spring Boot, and associated technologies. Each exercise builds on previous knowledge, gradually increasing in complexity and covering essential aspects of Java development.

## Table of Contents

- [Exercise 1: Introduction to Spring Boot](#exercise-1-introduction-to-spring-boot)
- [Exercise 2: Working with JPA Entities](#exercise-2-working-with-jpa-entities)
- [Exercise 3: Creating Repositories and Services](#exercise-3-creating-repositories-and-services)
- [Exercise 4: Developing a Book Store API](#exercise-4-developing-a-book-store-api)
- [Exercise 5: Advanced Features in Book Store API](#exercise-5-advanced-features-in-book-store-api)
- [Exercise 6: User Registration and Authentication](#exercise-6-user-registration-and-authentication)
- [Exercise 7: Testing the Book Store API](#exercise-7-testing-the-book-store-api)

---

## Exercise 1: Introduction to Spring Boot

In this exercise, a basic Spring Boot application is set up. The goal is to familiarize with the structure of a Spring Boot project, including the configuration files and the initial setup required to get a project up and running.

## Exercise 2: Working with JPA Entities

This exercise dives into the Java Persistence API (JPA). I've created entity classes that represent database tables, and explored how to map these entities to database schema using annotations.

## Exercise 3: Creating Repositories and Services

Here, repositories are implemented that interact with the database and services that contain business logic. This exercise helps to understand how to separate data access and business logic layers in a Spring Boot application.

## Exercise 4: Developing a Book Store API

In this exercise, developed a simple RESTful API for a book store. The project includes creating endpoints for managing books and customers, handling CRUD operations, and understanding the flow from the controller to the database.

## Exercise 5: Advanced Features in Book Store API

This exercise extends the Book Store API with advanced features such as custom queries, error handling, and optimization of service logic. 

## Exercise 6: User Registration and Authentication

Security is the focus of this exercise. The user registration and authentication mechanisms are implemented, securing the API endpoints and managing user sessions effectively.

## Exercise 7: Testing the Book Store API

The final exercise is all about ensuring the robustness of the application. Unit and integration tests for the Book Store API is written, using testing frameworks to validate the functionality and reliability of my code.

---

Each exercise folder contains the source code, configuration files, and other necessary resources. The instructions provided in the code comments and the documentation within each folder to complete the exercises.

# Week 5 Exercises

This repository contains the exercises for Week 5, each focused on developing and refining the `BookStoreAPI` project. Below is an overview of the exercises included:

## Exercises Overview

### Exercise 8
- **Contents:**
  - `.gitignore`: Specifies files and directories that Git should ignore.
  - `.metadata`: Contains IDE or project-specific configuration files.
  - `BookStoreAPI`: The main project directory containing the codebase.

### Exercise 9
- **Contents:**
  - `.gitignore`: Specifies files and directories that Git should ignore.
  - `.metadata`: Contains IDE or project-specific configuration files.
  - `BookStoreAPI`: The main project directory containing the codebase.

### Exercise 10
- **Contents:**
  - `BookStoreAPI`: The main project directory containing the codebase.

### Exercise 11
- **Contents:**
  - `.gitignore`: Specifies files and directories that Git should ignore.
  - `.metadata`: Contains IDE or project-specific configuration files.
  - `BookStoreAPI`: The main project directory containing the codebase.

### Exercise 12
- **Contents:**
  - `.gitignore`: Specifies files and directories that Git should ignore.
  - `.metadata`: Contains IDE or project-specific configuration files.
  - `BookStoreAPI`: The main project directory containing the codebase.

### Exercise 13
- **Contents:**
  - `.gitignore`: Specifies files and directories that Git should ignore.
  - `.metadata`: Contains IDE or project-specific configuration files.
  - `BookStoreAPI`: The main project directory containing the codebase.

### Exercise 14
- **Contents:**
  - `.gitignore`: Specifies files and directories that Git should ignore.
  - `.metadata`: Contains IDE or project-specific configuration files.
  - `BookStoreAPI`: The main project directory containing the codebase.

### Exercise 15
- **Contents:**
  - `BookStoreAPI`: The main project directory containing the codebase.
