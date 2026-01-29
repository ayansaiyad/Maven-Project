# Maven-Project

A Maven-based Java application for processing user activities.

## Prerequisites

- Java Development Kit (JDK) 17 or higher
- Apache Maven 3.6 or higher

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Maven-Project
```

2. Build the project:
```bash
mvn clean install
```

## Usage

Run the application:
```bash
java -cp target/my-app-1.0-SNAPSHOT.jar com.myapp.App
```

Expected output:
```
Hello World!
```

## Building the Project

Build the project:
```bash
mvn clean install
```

Build without running tests:
```bash
mvn clean package -DskipTests
```

## Running Tests

Run all tests:
```bash
mvn test
```

Test reports are available in `target/surefire-reports/` directory.

## Code Coverage

Generate code coverage report:
```bash
mvn clean test jacoco:report
```

View the coverage report by opening `target/site/jacoco/index.html` in your browser.

## Project Structure

```
my-app/
├── src/
│   ├── main/java/com/myapp/App.java
│   └── test/java/com/myapp/AppTest.java
├── target/
├── pom.xml
└── README.md
```

## Technologies Used

- Java 17
- Maven
- JUnit 5
- JaCoCo

## Maven Commands

| Command | Description |
|---------|-------------|
| `mvn clean` | Remove build artifacts |
| `mvn compile` | Compile source code |
| `mvn test` | Run unit tests |
| `mvn package` | Create JAR file |
| `mvn install` | Install to local repository |

## License

This project is licensed under the MIT License.
