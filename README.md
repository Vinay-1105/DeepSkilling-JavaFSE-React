# DeepSkilling Java FSE - Angular React Masterclass 🚀

## 📚 Overview

**Deep Skilling Java FSE (Full Stack Engineering)** is a 7-week intensive masterclass covering:
- Backend: Java, Spring Framework, REST APIs, Microservices
- Database: JPA, Hibernate, SQL
- Frontend: React, Angular
- DevOps: Docker, Kubernetes, Cloud Deployment

**Current Status**: ✅ **Weeks 1-2 Complete** (52/52 Tests Passing)

---

## 🎯 Project Progression

### Week 1: Design Patterns, DSA, TDD ✅ (COMPLETE)
**Date**: 25-June-2026 | **Tests**: 25/25 ✅

**Topics Covered**:
- JUnit 4 Testing Framework
- Mockito Mocking Library
- SLF4J Logging Framework
- Design Patterns Implementation
- Data Structures & Algorithms
- Test-Driven Development (TDD)

**Modules**:
- ✅ `JUnit-Mockito-SLF4J` - 25 tests passing

---

### Week 2: Spring Core, JPA, Hibernate ✅ (COMPLETE)
**Date**: 27-June-2026 | **Tests**: 27/27 ✅

**Topics Covered**:
- Spring Framework 6.1.0
- Dependency Injection (DI)
- Bean Management & Configuration
- JPA 2.2 Entity Mapping
- Hibernate 5.6.15 ORM
- H2 In-Memory Database

**Modules**:
- ✅ `SpringCore-Exercises` - 10 tests
- ✅ `JPA-Exercises` - 10 tests
- ✅ `Hibernate-Exercises` - 7 tests

---

### Week 3: Spring REST APIs ⏳ (UPCOMING)
**Date**: 02-July-2026

**Topics To Cover**:
- REST Controller Development
- HTTP Methods (GET, POST, PUT, DELETE)
- Request/Response Handling
- Exception Management
- Request Validation
- REST API Testing

---

### Week 4: SonarQube & Microservices ⏳ (UPCOMING)
**Date**: 09-July-2026

---

### Week 5: React Fundamentals ⏳ (UPCOMING)
**Date**: 16-July-2026

---

### Week 6: React Advanced ⏳ (UPCOMING)
**Date**: 23-July-2026

---

### Week 7: DevOps, Docker, Cloud, GenAI ⏳ (UPCOMING)
**Date**: 28-July-2026

---

## 📊 Test Results Summary

| Week | Module | Tests | Status |
|------|--------|-------|--------|
| 1 | JUnit-Mockito-SLF4J | 25/25 | ✅ PASS |
| 2 | Spring Core | 10/10 | ✅ PASS |
| 2 | JPA Exercises | 10/10 | ✅ PASS |
| 2 | Hibernate Exercises | 7/7 | ✅ PASS |
| **TOTAL** | **4 Modules** | **52/52** | **✅ PASS** |

---

## 🛠️ Technology Stack

### Backend
- **Language**: Java 21
- **Build Tool**: Maven 3.9.16
- **Frameworks**:
  - Spring Framework 6.1.0
  - Spring Boot 3.x (Week 3+)
  - JPA 2.2
  - Hibernate 5.6.15

### Database
- H2 (In-Memory Testing)
- MySQL/Oracle (Production)

### Testing
- JUnit 4.13.2
- Mockito 5.11.0
- Maven Surefire 2.22.2

### Logging
- SLF4J 2.0.7
- Logback 1.4.11

### Frontend (Week 5-6)
- React 18+
- Angular 17+

### DevOps (Week 7)
- Docker
- Kubernetes
- AWS/Cloud Platforms

---

## 📁 Repository Structure
DeepSkilling-JavaFSE-Angular-React-/

│

├── Week1-DesignPatterns-DSA-PLSQL-TDD/

│   └── JUnit-Mockito-SLF4J/

│       ├── src/main/java/

│       ├── src/test/java/

│       ├── pom.xml

│       └── README.md

│

├── Week2-SpringCore-JPA-Hibernate/

│   ├── SpringCore-Exercises/

│   │   ├── src/main/java/com/deepskilling/springcore/

│   │   ├── src/test/java/

│   │   └── pom.xml

│   │

│   ├── JPA-Exercises/

│   │   ├── src/main/java/com/deepskilling/jpa/

│   │   ├── src/test/java/

│   │   ├── src/main/resources/META-INF/persistence.xml

│   │   └── pom.xml

│   │

│   └── Hibernate-Exercises/

│       ├── src/main/java/com/deepskilling/hibernate/

│       ├── src/test/java/

│       ├── src/main/resources/hibernate.cfg.xml

│       └── pom.xml

│

├── Week3-SpringREST/ (Upcoming)

├── Week4-Microservices/ (Upcoming)

├── Week5-React/ (Upcoming)

├── Week6-ReactAdvanced/ (Upcoming)

├── Week7-DevOps/ (Upcoming)

│

└── README.md (This file)

---

## 🚀 Getting Started

### Prerequisites

```bash
# Required
- Java 21+
- Maven 3.9.16+
- Git
- VS Code or IntelliJ IDEA

# Verify Installation
java -version        # Java 21.0.4
mvn -version        # Apache Maven 3.9.16
```

### Installation

```bash
# Clone Repository
git clone https://github.com/Vinay-1105/DeepSkilling-JavaFSE-Angular-React-.git
cd DeepSkilling-JavaFSE-Angular-React-

# Navigate to specific week/module
cd Week1-DesignPatterns-DSA-PLSQL-TDD/JUnit-Mockito-SLF4J/

# Install Dependencies & Run Tests
mvn clean test
```

### Running Individual Modules

```bash
# Week 1
cd Week1-DesignPatterns-DSA-PLSQL-TDD/JUnit-Mockito-SLF4J/
mvn clean test

# Week 2 - Spring Core
cd Week2-SpringCore-JPA-Hibernate/SpringCore-Exercises/
mvn clean test

# Week 2 - JPA
cd Week2-SpringCore-JPA-Hibernate/JPA-Exercises/
mvn clean test

# Week 2 - Hibernate
cd Week2-SpringCore-JPA-Hibernate/Hibernate-Exercises/
mvn clean test
```

---

## 📖 Module Descriptions

### Week 1: JUnit-Mockito-SLF4J
**Focus**: Unit Testing, Mocking, Logging

**What You'll Learn**:
- Writing comprehensive unit tests with JUnit 4
- Mocking external dependencies with Mockito
- Implementing structured logging with SLF4J/Logback
- Test-Driven Development (TDD) methodology

**Test Coverage**: 25 tests
- AssertionsTest (5 tests)
- BankAccountTest (5 tests)
- CalculatorTest (5 tests)
- OrderServiceTest (5 tests)
- LoggingIntegrationTest (2 tests)
- WeatherServiceTest (3 tests)

---

### Week 2: Spring Core
**Focus**: Dependency Injection, Bean Management

**What You'll Learn**:
- Spring Framework fundamentals
- Constructor & Setter injection
- Bean lifecycle & scope
- Configuration with annotations
- Spring context management

**Test Coverage**: 10 tests

---

### Week 2: JPA Exercises
**Focus**: Entity Mapping, CRUD Operations

**What You'll Learn**:
- JPA annotations & entity mapping
- Relationship mapping (One-to-One, One-to-Many)
- CRUD operations
- Persistence context management
- H2 database integration

**Test Coverage**: 10 tests

---

### Week 2: Hibernate Exercises
**Focus**: ORM Framework, Session Management

**What You'll Learn**:
- Hibernate ORM framework
- Session & transaction management
- Repository pattern implementation
- HQL queries
- Performance optimization
