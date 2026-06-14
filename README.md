# Financial Advisor Data Model

A Java Spring Boot data modeling project based on a financial advisor portfolio management system.

## Overview

This project implements a relational data model for a financial advisory platform. The system is designed to help financial advisors manage clients, portfolios, and investment securities.

The application uses Java Persistence API (JPA) annotations to model database entities and relationships.

## Features

* Manage financial advisors and their clients
* Create and maintain client portfolios
* Track securities owned within portfolios
* Implement entity relationships using JPA
* Auto-generated primary keys
* Relational database design

## Data Model

### Advisor

* advisorId
* firstName
* lastName
* address
* phone
* email

### Client

* clientId
* advisor
* firstName
* lastName
* address
* phone
* email

### Portfolio

* portfolioId
* client
* creationDate

### Security

* securityId
* portfolio
* name
* category
* purchasePrice
* purchaseDate
* quantity

## Relationships

* One Advisor can manage multiple Clients
* One Client has one Portfolio
* One Portfolio can contain multiple Securities

## Technologies Used

* Java
* Spring Boot
* Jakarta Persistence API (JPA)
* Maven
* Git & GitHub

## Learning Outcomes

Through this project I gained experience with:

* Entity Relationship Diagram (ERD) design
* Relational database modeling
* JPA entity creation and annotations
* Primary and foreign key relationships
* Git version control
* Maven project management

## Project Origin

This project was completed as part of the Wells Fargo Software Engineering Job Simulation on Forage.

