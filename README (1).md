# Spring Framework, Spring Boot & Microservices Training

## Course Overview

This course provides a structured, hands-on learning path from **Spring Core** fundamentals to **Spring Boot, REST APIs, Spring Data JPA, Microservices, Spring Cloud**, and a final **Customer Portfolio Management** project.

The course progresses from dependency injection and Spring container concepts to production-oriented microservices concepts such as **Eureka Service Discovery, OpenFeign, Load Balancing, API Gateway, Config Server, Resilience4j, and Actuator**.

---

## Course Objectives

By the end of this course, learners will be able to:

- Understand the fundamentals of the Spring Framework and Spring modules.
- Configure and manage Spring beans using XML, annotations, and Java configuration.
- Implement Dependency Injection and Autowiring.
- Understand Spring Bean lifecycle and bean scopes.
- Build applications using Spring JDBC and Spring MVC.
- Develop RESTful APIs using Spring Boot.
- Integrate Spring Boot applications with MySQL.
- Use Spring Data JPA and repository abstractions.
- Understand monolithic and microservices architectures.
- Develop microservices and implement interservice communication.
- Implement service registration and discovery using Eureka.
- Implement communication using OpenFeign.
- Apply client-side load balancing using Spring Cloud Load Balancer.
- Configure routing through Spring Cloud API Gateway.
- Externalize configuration using Spring Cloud Config Server and Git.
- Implement fault tolerance using Resilience4j.
- Monitor applications using Spring Boot Actuator.
- Develop a complete microservices-based Customer Portfolio Management application.

---

# Course Structure

## Day 01 — Spring Core Fundamentals

### Session 01 — Introduction to Spring Framework
**Duration:** 2 Hours

Topics:

- Overview of Spring Framework
- Features of Spring Framework
  - Lightweight
  - Inversion of Control (IoC)
  - Spring Container
  - Exception Handling
  - Integration with other frameworks
  - Spring MVC

### Overview of Spring Modules

- Overview of Spring Framework modules
- Spring Core
- Spring Web
- Spring Data Access/Integration

### Session 02 — Setting Up Spring and Spring Containers

**Setting Up Spring — 1 Hour**

- Setting up Spring Environment
- Using Eclipse
- Using Spring Tool Suite (STS)

**Spring Containers — 2 Hours**

- Spring IoC Containers
- BeanFactory
- XmlBeanFactory
- ApplicationContext
- ClassPathXmlApplicationContext
- FileSystemXmlApplicationContext
- AnnotationConfigApplicationContext
- ConfigurableApplicationContext
- BeanFactory vs ApplicationContext

**Hands-on — 1 Hour**

- Working with Spring Container

---

## Day 02 — Spring Configuration, Dependency Injection & Beans

### Session 01 — Spring Configuration Metadata
**Duration:** 2 Hours

Topics:

- Spring Configuration Metadata
- XML Configuration
- Java-based Configuration
- Annotation-based Configuration

### Dependency Injection (DI)
**Duration:** 2 Hours

Topics:

- Understanding Dependency Injection
- Types of Dependency Injection
- Constructor Injection
- Setter Injection
- Constructor Injection vs Setter Injection
- Field Injection
- Injecting Collections
  - List
  - Set
  - Map

### Session 02

**Hands-on — 1 Hour**

- Implementing Dependency Injection

### Spring Beans — 3 Hours

Topics:

- Introduction to Spring Beans
- Bean Lifecycle Callbacks
- Initialization Callback
- InitializingBean
- `init-method` in XML
- `@PostConstruct`
- Destruction Callback
- DisposableBean
- `destroy-method` in XML
- `@PreDestroy`
- Bean Scopes
- Singleton Scope
- Prototype Scope
- Shutting Down the IoC Container

---

## Day 03 — Autowiring and Spring Configuration

### Session 01 — Autowiring with XML
**Duration:** 3 Hours

Topics:

- Introduction to Autowiring
- Overview of Autowiring
- Importance of Autowiring
- Autowiring Modes
  - `no`
  - `byType`
  - `byName`
  - `constructor`
- Limitations of Autowiring

### Annotation-Based Configuration — Spring Core

Topics:

- Annotation-Based Configuration
- Turning on Annotations
- `@Autowired`
- `@Qualifier`
- `@Value`
- Stereotype Annotations
  - `@Component`
  - `@Service`
  - `@Controller`
  - `@Repository`

### Hands-on — 1 Hour

- Implementing Autowiring

### Session 02 — Java-Based Configuration
**Duration:** 2 Hours

Topics:

- Java-Based Configuration
- `@Configuration`
- `@Bean`
- `@Lazy`
- `@Scope`
- `@PropertySource`
- `@ComponentScan`

### Hands-on — 2 Hours

- Practice Spring Core configuration concepts

---

## Day 04 — Spring JDBC

### Session 01 — Spring JDBC
**Duration:** 4 Hours

Topics:

- Overview of Spring JDBC
- Advantages of Spring JDBC
- Spring JDBC Components
- DataSource
- JdbcTemplate
- Executing queries with JdbcTemplate

### Session 02 — Advanced JDBC Components
**Duration:** 2 Hours

Topics:

- JdbcTemplate
- ResultSetExtractor
- RowMapper
- NamedParameterJdbcTemplate
- SimpleJdbcCall

### Hands-on — 2 Hours

- Implementing database operations using Spring JDBC

---

## Day 05 — Spring MVC

### Session 01 — Introduction to Web Applications
**Duration:** 1 Hour

Topics:

- Introduction to Web Applications
- Three Layers in Web Applications
  - UI Layer
  - Service/Business Logic Layer
  - Data Layer

### Spring Web MVC — 3 Hours

Topics:

- Spring MVC Architecture and Flow
- Key Components
- DispatcherServlet
- HandlerMapping
- Controllers
- ModelAndView
- ViewResolver

### Session 02 — Configuring Spring MVC
**Duration:** 3 Hours

Topics:

- Configuring Spring MVC
- XML-based approach
- `@Controller`
- `@RequestMapping`
- ViewResolvers
- InternalResourceViewResolver
- XmlViewResolver
- ResourceBundleViewResolver

### Hands-on — 1 Hour

- Implementation of a simple Spring MVC application

---

## Day 06 — Spring MVC Request Handling, Forms, Validation & Logging

### Session 01 — Spring Web MVC
**Duration:** 4 Hours

Topics:

- Handling Request Data
- `@RequestParam`
- `@PathVariable`
- Binding Spring Form Data
- `@ModelAttribute`
- Handling Data in Spring MVC
- Model
- ModelMap
- ModelAndView
- Spring Form Validation
- Validation Annotations
- Spring Forms
- `@Valid`
- BindingResult
- Server-Side Logging
- Introduction to Logging
- Benefits of Logging
- Different Logging Levels

### Session 02 — Hands-on
**Duration:** 4 Hours

Topics:

- Creating Logger Object
- FileAppender
- Server-Side Logging
- CRUD Operations using Spring JDBC + Spring MVC

---

## Day 07 — Spring Boot and REST

### Session 01 — Introduction to Spring Boot
**Duration:** 1 Hour

Topics:

- Overview of Spring Boot
- Features and Benefits
- Getting Started with Spring Boot

### Spring Boot Setup — 1 Hour

- Setting up a Spring Boot project
- Java and starter dependencies

### Creating Spring Boot Application — 2 Hours

Topics:

- Creating a starter project with Maven
- Spring Boot current version
- Understanding Spring Boot annotations
- `@SpringBootApplication`
- Externalizing Configuration
- `application.properties`
- `application.yml`

### Spring Boot REST — 4 Hours

Topics:

- Introduction to RESTful Web Services
- Setting up Spring Boot for REST
- Creating RESTful Controllers
- `@RestController`
- `@Service`
- `@Repository`
- Request Mapping
- `@RequestMapping`
- `@GetMapping`
- `@PostMapping`
- `@DeleteMapping`
- `@PutMapping`
- Request and Response Handling
- `@RequestBody`
- `@ResponseBody`
- `ResponseEntity`
- HTTP Methods
- HTTP Status Codes
- Best Practices for RESTful Services

---

## Day 08 — REST API, JDBC & Spring Data JPA

### Session 01 — REST API Hands-on
**Duration:** 2 Hours

Task:

- Build a simple REST API using different HTTP methods.
- Test REST endpoints using POSTMAN.

### Spring Boot with Database — 2 Hours

Topics:

- Spring Boot Starter JDBC
- Integrating Spring Boot with MySQL

### Session 02 — Spring Data JPA
**Duration:** 3 Hours

Topics:

- Overview of ORM
- Getting Started with Spring Data JPA
- Connecting to MySQL
- JPA Concepts
- JPA-Based Annotations
  - `@Entity`
  - `@Table`
  - `@Id`
  - `@Column`
  - `@GeneratedValue`
- Spring Data Repositories
- CrudRepository
- JpaRepository

### Hands-on — 1 Hour

- Implementing Spring Data JPA

---

## Day 09 — Spring Data JPA & Introduction to Microservices

### Session 01 — Spring Data JPA
**Duration:** 1.5 Hours

Topics:

- Deep Dive into JpaRepository
- Query Methods
- `findBy...`
- `@Query`
- Native Queries

### Introduction to Microservices — 1 Hour

Topics:

- Introduction to Monolithic Architecture
- Definition and Characteristics
- Architecture Components
- Drawbacks of Monolithic Architecture
- Introduction to Microservices
- Definition and Characteristics
- Microservices Architecture
- Benefits
- Drawbacks
- Monolithic vs Microservice Architecture

### Microservices Use Cases — 1 Hour

Topics:

- Scenarios where Microservices are beneficial
- Scalability
- Flexibility and Agility
- Fault Isolation
- Polyglot Persistence
- Resilience and High Availability
- Real-time Applications using Microservices
- Industry Examples
  - Netflix
  - Uber
  - Slack
  - Airbnb
  - Spotify

### Hands-on — 0.5 Hour

- Create a simple Microservice
- Test endpoints using POSTMAN

### Session 02 — Microservice Communication using RestTemplate
**Duration:** 1 Hour

Topics:

- Interservice Communication using RestTemplate

### Hands-on — 1 Hour

- Implement interservice communication

### Spring Cloud — 1 Hour

Topics:

- Introduction to Spring Cloud
- Role of Spring Cloud in Microservices Development

### Service Registry and Discovery — 1 Hour

Topics:

- Introduction to Service Registry
- Introduction to Service Discovery
- Service Registration with Eureka Server

---

## Day 10 — Eureka, OpenFeign, Load Balancing & API Gateway

### Session 01 — Service Registry and Discovery
**Duration:** 1 Hour

Topics:

- Service Discovery with Eureka Client
- Viewing Microservices in Eureka Dashboard
- Accessing Microservices from Eureka Dashboard
- `@EnableEurekaServer`
- `@EnableDiscoveryClient`

### Hands-on — 1 Hour

- Microservices Eureka Registration

### Microservice Communication using OpenFeign — 2 Hours

Topics:

- Interservice Communication using OpenFeign

### Session 02 — Load Balancing
**Duration:** 1 Hour

Topics:

- Introduction to Load Balancing
- Need for Load Balancing in Microservices
- Spring Cloud Load Balancer (SLB)
- Client-Side Load Balancer
- Server-Side Load Balancer
- Client-Side vs Server-Side Load Balancing

### Hands-on — 1 Hour

- Implement Load Balancing on Microservices

### Spring Cloud API Gateway — 2 Hours

Topics:

- Introduction to API Gateway
- Spring Cloud API Gateway Overview
- Configuring Spring Cloud API Gateway
- Java-Based Configuration
- Annotation-Based Configuration
- Routing using API Gateway

---

## Day 11 — Config Server, Fault Tolerance & Actuator

### Session 01 — Spring Cloud Config Server
**Duration:** 2 Hours

Topics:

- Overview of Spring Cloud Config Server
- Importance of Externalizing Configuration
- Setting up Spring Cloud Config Server
- Fetching Configuration from Git Repository

### Hands-on — 2 Hours

- Spring Cloud API Gateway
- Spring Cloud Config Server

### Session 02 — Fault Tolerance
**Duration:** 1 Hour

Topics:

- Introduction to Fault Tolerance
- Need for Fault Tolerance
- Fault Tolerance using Resilience4j

### Spring Boot Actuator — 1 Hour

Topics:

- Introduction to Actuator
- Integrating Actuator
- Configuring Actuator
- Exploring Built-in Endpoints through HTTP

### Hands-on — 2 Hours

- Implement Fault Tolerance
- Implement and explore Actuator

---

# Day 12 — Hands-on Project: Customer Portfolio Management

## Session 01 — Project Implementation
**Duration:** 4 Hours

### Project: Customer Portfolio Management

Implement a microservices-based Customer Portfolio Management system.

### Session 02 — Customer Service
**Duration:** 2 Hours

Requirement:

Build a service to manage all customers of the bank.

Operations:

- Add Customer
- Search Customer
- Update Customer
- Delete Customer

### Stocks Service
**Duration:** 2 Hours

Requirement:

Build a service to manage all stocks owned by a customer.

Operations:

- Add Stock
- Delete Stock

---

# Day 13 — Banks, KYC & REST APIs

## Session 01 — Banks
**Duration:** 2 Hours

Requirement:

Build a service to manage all bank accounts of customers.

Operations:

- Add Bank Account
- Edit Bank Account
- Update Bank Account
- Delete Bank Account

### KYC
**Duration:** 2 Hours

Requirement:

Build a service to manage customer KYC details.

KYC details include:

- PAN Card
- Aadhaar Card
- Passport Details

Operations:

- Add KYC
- Edit KYC
- Search KYC

### Session 02 — REST APIs
**Duration:** 4 Hours

Develop the following REST APIs:

```text
/customers
/customers/{cust-id}
/customers/{cust-id}/stocks
/customers/{cust-id}/banks
/customers/{cust-id}/kyc
```

---

# Day 14 — REST API Completion

## Session 01
**Duration:** 4 Hours

Continue developing the Customer Portfolio Management REST APIs.

Additional APIs:

```text
/customers/{cust-id}/kyc/pan
/customers/{cust-id}/kyc/aadhar
```

---

# Technology Stack

| Area | Technologies / Concepts |
|---|---|
| Language | Java |
| Framework | Spring Framework |
| Spring Core | IoC, DI, Beans, Autowiring |
| Configuration | XML, Annotations, Java Configuration |
| Database Access | Spring JDBC |
| Web Framework | Spring MVC |
| Application Framework | Spring Boot |
| API Development | RESTful Web Services |
| API Testing | POSTMAN |
| Database | MySQL |
| ORM | JPA |
| Persistence | Spring Data JPA |
| Repository | CrudRepository, JpaRepository |
| Architecture | Microservices |
| Service Communication | RestTemplate, OpenFeign |
| Service Discovery | Eureka |
| Load Balancing | Spring Cloud Load Balancer |
| Gateway | Spring Cloud API Gateway |
| Configuration | Spring Cloud Config Server |
| Configuration Source | Git Repository |
| Fault Tolerance | Resilience4j |
| Monitoring | Spring Boot Actuator |
| Build Tool | Maven |
| IDE | Eclipse / Spring Tool Suite |

---

# Hands-on Progression

The course follows a practical progression:

```text
Spring Core
    ↓
IoC Container
    ↓
Dependency Injection
    ↓
Spring Beans
    ↓
Autowiring
    ↓
Java / Annotation Configuration
    ↓
Spring JDBC
    ↓
Spring MVC
    ↓
Spring Boot
    ↓
REST APIs
    ↓
MySQL + Spring Data JPA
    ↓
Microservices
    ↓
RestTemplate
    ↓
Spring Cloud
    ↓
Eureka Service Discovery
    ↓
OpenFeign
    ↓
Load Balancing
    ↓
API Gateway
    ↓
Config Server
    ↓
Resilience4j
    ↓
Actuator
    ↓
Customer Portfolio Management Project
```

---

# Final Project — Customer Portfolio Management

## Project Goal

Develop a microservices-based banking application for managing a customer's portfolio.

## Core Microservices

```text
Customer Service
       |
       +---- Stocks Service
       |
       +---- Banks Service
       |
       +---- KYC Service
```

## Customer Management

```text
POST   /customers
GET    /customers
GET    /customers/{cust-id}
PUT    /customers/{cust-id}
DELETE /customers/{cust-id}
```

## Stock Management

```text
POST   /customers/{cust-id}/stocks
DELETE /customers/{cust-id}/stocks/{stock-id}
```

## Bank Account Management

```text
POST   /customers/{cust-id}/banks
PUT    /customers/{cust-id}/banks/{bank-id}
DELETE /customers/{cust-id}/banks/{bank-id}
```

## KYC Management

```text
POST   /customers/{cust-id}/kyc
GET    /customers/{cust-id}/kyc
PUT    /customers/{cust-id}/kyc

GET    /customers/{cust-id}/kyc/pan
GET    /customers/{cust-id}/kyc/aadhar
```

> The detailed HTTP methods for the final project should be aligned with the implementation requirements and API design agreed during the project.

---

# Learning Outcomes

After completing the course, learners should be able to:

1. Explain Spring Framework architecture and major modules.
2. Configure Spring applications using XML, annotations, and Java configuration.
3. Implement IoC and Dependency Injection.
4. Manage Spring Bean lifecycle and scopes.
5. Implement Autowiring using XML and annotations.
6. Develop database applications using Spring JDBC.
7. Build Spring MVC applications.
8. Handle request parameters, path variables, forms, validation, and logging.
9. Build REST APIs using Spring Boot.
10. Integrate Spring Boot with MySQL.
11. Implement persistence using Spring Data JPA.
12. Create and communicate between microservices.
13. Implement service discovery with Eureka.
14. Implement interservice communication with OpenFeign.
15. Implement load balancing using Spring Cloud Load Balancer.
16. Route requests using Spring Cloud API Gateway.
17. Externalize configuration using Spring Cloud Config Server.
18. Implement fault tolerance using Resilience4j.
19. Monitor applications using Spring Boot Actuator.
20. Build a complete microservices-based Customer Portfolio Management application.

---

# Recommended Repository Structure

A possible final project structure:

```text
customer-portfolio-management/
│
├── customer-service/
├── stock-service/
├── bank-service/
├── kyc-service/
│
├── eureka-server/
├── api-gateway/
├── config-server/
│
└── config-repository/
```

---

# Assessment Areas

Learners can be assessed through:

- Conceptual understanding
- Configuration exercises
- Coding exercises
- REST API implementation
- Database integration
- Microservice development
- Interservice communication
- Service discovery
- Load balancing
- API Gateway configuration
- Configuration management
- Fault tolerance
- Application monitoring
- Final project implementation

---

# Course Completion Checklist

- [ ] Spring Framework fundamentals
- [ ] Spring Modules
- [ ] Spring IoC Containers
- [ ] XML Configuration
- [ ] Annotation Configuration
- [ ] Java Configuration
- [ ] Dependency Injection
- [ ] Collection Injection
- [ ] Spring Bean Lifecycle
- [ ] Bean Scopes
- [ ] XML Autowiring
- [ ] Annotation-Based Autowiring
- [ ] Spring JDBC
- [ ] Spring MVC
- [ ] Form Handling
- [ ] Validation
- [ ] Logging
- [ ] Spring Boot
- [ ] REST APIs
- [ ] POSTMAN Testing
- [ ] MySQL Integration
- [ ] Spring Data JPA
- [ ] JpaRepository
- [ ] Query Methods
- [ ] Native Queries
- [ ] Microservices Architecture
- [ ] RestTemplate
- [ ] Spring Cloud
- [ ] Eureka
- [ ] OpenFeign
- [ ] Load Balancing
- [ ] API Gateway
- [ ] Config Server
- [ ] Resilience4j
- [ ] Actuator
- [ ] Customer Portfolio Management Project

---

# End-to-End Course Outcome

The learner moves from **Spring Framework fundamentals** to building and integrating a **production-oriented microservices application** using the Spring ecosystem.

```text
FOUNDATION
Spring Core → IoC → DI → Beans
       ↓
WEB & DATA
Spring JDBC → Spring MVC → Spring Boot → REST → JPA
       ↓
MICROSERVICES
Microservices → RestTemplate → Spring Cloud
       ↓
DISTRIBUTED SYSTEMS
Eureka → OpenFeign → Load Balancer → API Gateway
       ↓
PRODUCTION CONCERNS
Config Server → Resilience4j → Actuator
       ↓
CAPSTONE
Customer Portfolio Management
```
