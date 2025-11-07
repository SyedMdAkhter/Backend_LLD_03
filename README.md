# Backend_LLD_03
Backend code for Tic-Tac-Toe, Parking Lot, BookMyShow and Splitwise

## Overview
This repository contains Low-Level Design (LLD) implementations for four popular backend systems:
1. **Tic-Tac-Toe** - Classic game implementation
2. **Parking Lot** - Parking management system
3. **BookMyShow** - Movie ticket booking system
4. **Splitwise** - Expense sharing application

## Prerequisites
- Java 17 or higher
- Maven 3.6 or higher

## Project Structure
```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── backend/
│   │           └── lld/
│   │               ├── tictactoe/
│   │               ├── parkinglot/
│   │               ├── bookmyshow/
│   │               └── splitwise/
│   └── resources/
│       └── logback.xml
└── test/
    ├── java/
    │   └── com/
    │       └── backend/
    │           └── lld/
    │               ├── tictactoe/
    │               ├── parkinglot/
    │               ├── bookmyshow/
    │               └── splitwise/
    └── resources/
```

## Dependencies
The project includes the following key dependencies:
- **Lombok** - Reduces boilerplate code
- **SLF4J + Logback** - Logging framework
- **JUnit 5** - Testing framework
- **Mockito** - Mocking framework for tests
- **AssertJ** - Fluent assertions for tests
- **Apache Commons** - Utility libraries
- **Guava** - Google's core libraries
- **Jackson** - JSON processing

## Build and Run

### Build the project
```bash
mvn clean install
```

### Run tests
```bash
mvn test
```

### Compile only
```bash
mvn compile
```

## Applications

### 1. Tic-Tac-Toe
See [tictactoe/README.md](src/main/java/com/backend/lld/tictactoe/README.md) for details.

### 2. Parking Lot
See [parkinglot/README.md](src/main/java/com/backend/lld/parkinglot/README.md) for details.

### 3. BookMyShow
See [bookmyshow/README.md](src/main/java/com/backend/lld/bookmyshow/README.md) for details.

### 4. Splitwise
See [splitwise/README.md](src/main/java/com/backend/lld/splitwise/README.md) for details.

## Development Guidelines
- Follow SOLID principles
- Use design patterns where appropriate
- Write unit tests for all business logic
- Use Lombok annotations to reduce boilerplate
- Follow Java naming conventions
- Keep classes focused and cohesive

## License
MIT License
