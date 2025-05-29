# Study Point

**Study Point** is a web-based application designed to manage and organize educational content efficiently. Built using Java and Spring Boot, it provides a robust backend infrastructure for handling various academic resources.

## Features

- **Resource Management**: Add, update, and delete study materials.
- **User Authentication**: Secure login and registration system.
- **Database Integration**: Seamless interaction with relational databases.
- **RESTful APIs**: Efficient communication between frontend and backend.
- **Scalable Architecture**: Designed to accommodate future enhancements.

## Tech Stack

- **Backend**:
  - Java
  - Spring Boot
  - Maven
  - MySQL

- **Frontend**:
  - HTML
  - CSS
  - JavaScript

## Getting Started

### Prerequisites

- Java 8 or higher
- Maven
- MySQL
- Node.js and npm (for frontend dependencies)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Abhishek-kumar90/Study-point.git
   cd Study-point
Database Setup:

Create a MySQL database named study_point.

Import the springproject.sql file located in the root directory to set up the necessary tables.

Backend Setup:

Navigate to the project directory:

bash
Copy
Edit
cd Study-point
Configure the application.properties file with your MySQL credentials:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/study_point
spring.datasource.username=your_username
spring.datasource.password=your_password
Build the project using Maven:

bash
Copy
Edit
mvn clean install
Run the application:

bash
Copy
Edit
mvn spring-boot:run
The backend server will start on http://localhost:8080.

Frontend Setup:

Navigate to the src/main/resources/static directory:

bash
Copy
Edit
cd src/main/resources/static
Install frontend dependencies (if any):

bash
Copy
Edit
npm install
Since the frontend is served by Spring Boot, no separate command is needed to run it.

Access the Application:

Open your browser and navigate to http://localhost:8080 to use the Study Point application.
