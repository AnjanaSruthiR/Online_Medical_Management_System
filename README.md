# Hospital Management Application

## Overview
Hospital Management Application is a comprehensive desktop solution designed to streamline hospital operations, manage patient data, and support effective clinical workflows. Built using **Java Swing** for the graphical interface and **Java** for the core logic, this application integrates with **MySQL** to ensure secure and efficient data management.

## Features
- **Intuitive User Interface:** Developed with Java Swing to enhance usability and accessibility.
- **Comprehensive Data Management:** Supports complete CRUD operations for patient records and other hospital data.
- **Secure Protocols:** Implements data protection measures and role-based access control to safeguard sensitive information.
- **Modular Architecture:** A layered design separating frontend, backend services, and database components for maintainability and scalability.
- **Authentication Module:** Role-based access control for different hospital stakeholders.
- **Reporting & Analytics:** Generate reports for hospital management insights.

## Technologies Used
- **Frontend:** Java Swing (GUI framework for desktop applications)
- **Backend:** Java (Business logic and data processing)
- **Database:** MySQL (Secure storage and schema management)

## Architecture & Design
The project follows a **modular and layered architecture**:
- **Frontend:** Java Swing-based UI providing an interactive dashboard.
- **Backend:** Java services that handle business logic, data processing, and secure communication with the database.
- **Database:** MySQL is used to manage hospital data, enforce schema constraints, and support CRUD operations.

### System Components
Refer to the project diagrams for more details:
- **[High-Level Component Diagram](./High_level_component_diagram.pdf)**
- **[UML Class Diagram](./UML_Class_Diagram.pdf)**

## Setup & Installation
### Prerequisites
- Java JDK (version 8 or later)
- MySQL Server
- IDE (Eclipse, IntelliJ, or NetBeans recommended)

### Installation Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/AnjanaSruthiR/Online_Medical_Management_System.git
   ```
2. **Configure the Database:**
   - Install and run MySQL Server.
   - Create a new database and update the connection settings in the application configuration file.
3. **Compile & Run:**
   - Open the project in your preferred IDE.
   - Compile the source code and run the main application class to launch the Hospital Management Application.

## Usage
- **Login & Role-Based Access:** Secure login for different user roles ensures that each user has access only to the functionalities relevant to their responsibilities.
- **Dashboard Navigation:** The main dashboard provides access to modules for patient registration, appointment scheduling, and report generation.
- **Data Management:** Easily add, update, view, or delete records via an intuitive interface.
