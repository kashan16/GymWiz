
### Project Description

GymWiz is a comprehensive fitness tracking and workout planning application. This repository contains the backend of the GymWiz project, built with Spring Boot.

### Features

- RESTful API for managing workouts, exercises, and user data
- User Authentication and Authorization
- Database Integration with JPA
- Secure data storage

### Technologies Used

- **Spring Boot**
- **Java**
- **MySQL** / **PostgreSQL**

### Getting Started

#### Prerequisites

- [Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (JDK 11 or higher)
- [Maven](https://maven.apache.org/)
- [MySQL](https://dev.mysql.com/downloads/) or [PostgreSQL](https://www.postgresql.org/download/)

#### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/kashan16/GymWiz.git
   cd GymWiz/backend
   ```

2. **Configure Database:**

   Update the `application.properties` file in `src/main/resources` with your database connection details.

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your-database
   spring.datasource.username=your-username
   spring.datasource.password=your-password
   ```

3. **Build and Run the Application:**

   ```bash
   ./mvnw spring-boot:run
   ```

   The backend will be available at `http://localhost:8080`.

### Folder Structure

```plaintext
backend/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── gymwiz/
│   │   │           └── ...
│   │   ├── resources/
│   │   │   ├── application.properties
│   │   │   └── ...
│   └── test/
│       └── java/
│           └── com/
│               └── gymwiz/
│                   └── ...
├── mvnw
├── mvnw.cmd
├── pom.xml
└── ...
```

### Running Tests

```bash
./mvnw test
```
### Contributing

We welcome contributions to the GymWiz backend! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---