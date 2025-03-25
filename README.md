# Banking-App
Banking Application

#Overview: The Banking Application is a Spring Boot-based web application that provides banking functionalities such as account management, transactions, and user authentication.
# Banking Application

🔹 Features
- User authentication and authorization
- Account creation and management
- Fund transfer between accounts
- Transaction history
- REST API endpoints

🔹 Technologies Used
- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL/PostgreSQL (Database)
- Maven
- Apache Tomcat

🔹 Prerequisites
- JDK 17 or later
- Maven
- MySQL/PostgreSQL database
- Eclipse/IntelliJ IDEA (optional)

Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/banking-app.git
   cd banking-app
   ```

   Configure Database:
   Update `src/main/resources/application.properties` with your database configuration:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/banking_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```

3. Build and Run the Application:
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```

4. Access the Application:
   Open your browser and go to:
   ```
   http://localhost:8080
   ```

🔹 API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | /accounts | Get all accounts |
| POST | /accounts | Create a new account |
| GET | /transactions | Get transaction history |
| POST | /transfer | Transfer funds between accounts |

🔹 Testing
Run unit and integration tests using:
```sh
mvn test
```
