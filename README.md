Category & Product Management REST API

Spring Boot | JPA | Hibernate | MySQL | Pagination

📌 Project Overview

This project is a Spring Boot RESTful application developed as part of the Nimap Infotech Machine Test.

It provides CRUD operations for Category and Product entities with a one-to-many relationship, uses server-side pagination, and follows REST API best practices using Spring Data JPA & Hibernate with a relational database (MySQL).

🛠️ Tech Stack

Java 17+

Spring Boot

Spring Web (REST Controller)

Spring Data JPA

Hibernate

MySQL (RDBMS)

Maven

Annotation-based configuration (No XML)


🔗 Entity Relationship

Category → Product : One-to-Many

One Category can have multiple Products

While fetching a single product, its category details are also populated


📌 Pagination

Implemented using Spring Data JPA Pageable

Server-side pagination is mandatory and fully implemented

Page number is passed as a request parameter


✅ Key Features

REST Controller based APIs

Annotation-based configuration

Relational Database (MySQL)

JPA & Hibernate

One-to-Many entity mapping

Server-side pagination

Clean & modular code structure
