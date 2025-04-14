# Java Banking Application

This project is a **full-stack Java-based e-banking system** built by our team as part of the "Software Engineering" course. It allows users to manage transactions, apply for loans, generate cards, and more through an intuitive GUI. The system uses **JavaFX** for the interface, **Hibernate** for ORM, and **SQLite** for persistent data storage.

## Features

- User registration and login
- Deposit and withdrawal transactions
- Loan applications and tracking
- Card creation and management
- User-friendly GUI using JavaFX
- Data persistence using SQLite
- Object-Relational Mapping (ORM) with Hibernate

## Technologies Used

- Java (JDK 20.0.1)
- JavaFX (GUI)
- Maven (Dependency Management)
- Hibernate (ORM)
- SQLite (Database)
- IntelliJ IDEA (Recommended IDE)

## Getting Started

### Prerequisites

- Java SDK (OpenJDK 20.0.1)
- Maven
- IntelliJ IDEA (Recommended)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/banking-application.git
   cd banking-application

2. **Open the Project in IntelliJ IDEA**

⚠️ Note: Eclipse may have issues with project packages.

3. **Run the Application**

- Navigate to the gui package.

- Run the App.java file as the main class.

**Configuration**
- If using your own database, edit the connection URL in hibernate.cfg.xml.

- Maven will automatically handle all required dependencies.

- If changing the Hibernate version, ensure the correct SQLite dialect is used.
