# Patient Management System

A Java-based Patient Management System built using Spring Boot and Microservices Architecture. This project helps manage patient records and explores communication between different backend services.

## Technologies Used

- Java
- Spring Boot
- Microservices
- REST APIs
- PostgreSQL
- Apache Kafka
- gRPC
- Docker
- Maven

## Project Features

- Create, view, update, and delete patient records.
- Store patient information in a database.
- Use REST APIs for communication with the Patient Service.
- Use gRPC for communication between Patient and Billing Services.
- Use Apache Kafka for exchanging patient-related events.
- Explore containerization using Docker.

## Project Structure

- `patient-service` – Handles patient records and REST APIs.
- `billing-service` – Handles billing-related operations using gRPC.
- `analytics-service` – Consumes patient events using Kafka.
- `api-requests` – Contains API testing requests.
- `grpc-requests` – Contains gRPC testing requests.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/codeflashdemon/github-intellij-patientmanagement.git
   ```

2. Open the project in IntelliJ IDEA.

3. Configure the required database and Kafka settings.

4. Build the services using Maven:

   ```bash
   ./mvnw clean install
   ```

5. Run each Spring Boot service from IntelliJ IDEA.

## Future Improvements

I plan to add more features, explore new technologies, and enhance the overall functionality of this project as I continue learning and gaining experience.

## Author

**Jay Sharma**

- GitHub: https://github.com/codeflashdemon
- LinkedIn: https://www.linkedin.com/in/jay-sharma-537038354/
