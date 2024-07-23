---

# GymWiz

GymWiz is a comprehensive fitness tracking and workout planning application designed to help users achieve their health and fitness goals. Built with React and Spring Boot, GymWiz provides a seamless and interactive experience for managing workouts, tracking progress, and staying motivated.

## Features

- **User Authentication:** Secure sign-up and login functionalities with support for user account management.
- **Workout Creation and Management:** Create, update, and delete custom workout plans, including exercises, sets, and repetitions.
- **Progress Tracking:** Monitor workout history and track progress towards fitness goals.
- **Exercise Library:** Access a rich library of exercises with detailed descriptions and instructional media.
- **Personalized Recommendations:** Receive tailored workout and exercise recommendations based on user preferences and fitness levels.
- **Responsive Design:** Optimized for both desktop and mobile devices to ensure accessibility on the go.

## Technologies Used

- **Frontend:** React, TypeScript, Tailwind CSS
- **Backend:** Spring Boot
- **Database:** MySQL / PostgreSQL
- **DevOps:** Continuous Integration and Deployment (CI/CD)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (JDK 11 or higher)
- [Maven](https://maven.apache.org/) (for managing the Spring Boot project)
- [MySQL](https://dev.mysql.com/downloads/) or [PostgreSQL](https://www.postgresql.org/download/) (for the database)

### Frontend Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/kashan16/GymWiz.git
   cd GymWiz/frontend
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Run the Development Server:**
   ```bash
   npm start
   ```

   The frontend will be available at `http://localhost:3000`.

### Backend Setup

1. **Navigate to the Backend Directory:**
   ```bash
   cd GymWiz/backend
   ```

2. **Build and Run the Application:**
   ```bash
   ./mvnw spring-boot:run
   ```

   The backend will be available at `http://localhost:8080`.

3. **Configure Database:**
   - Update the `application.properties` file in `src/main/resources` with your database connection details.

### Running Tests

- **Frontend Tests:**
  ```bash
  npm test
  ```

- **Backend Tests:**
  ```bash
  ./mvnw test
  ```
## Contributing

We welcome contributions to GymWiz! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [React](https://reactjs.org/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Tailwind CSS](https://tailwindcss.com/)
- [MySQL](https://www.mysql.com/) / [PostgreSQL](https://www.postgresql.org/)

---

Feel free to adjust or expand the sections based on specific details or additional functionalities of the GymWiz project.