# CustomerRealtionManager
CRM using Java Simple and Basic Tool
# PulseCRM - Portfolio Edition

This is a modern Customer Relationship Management (CRM) system built with Spring Boot and a Vanilla JS frontend.

## Prerequisites

- **Java 17 or 21+** (Java 25 detected on this system)
- **MySQL Server**
- **Maven** (Not detected in PATH)

## Database Setup

1. Ensure MySQL is running.
2. Create a database named `crm_portfolio`:
   ```sql
   CREATE DATABASE crm_portfolio;
   ```
3. Update `src/main/resources/application.properties` with your MySQL credentials if they differ from:
   - **Username:** `root`
   - **Password:** `Karan@7871`

## How to Run

Since Maven is not currently in your system's PATH, you can run the project using one of the following methods:

### Method 1: Using an IDE (Recommended)
1. Open this folder in **IntelliJ IDEA**, **Eclipse**, or **VS Code**.
2. The IDE will recognize the `pom.xml` and download dependencies automatically.
3. Run the `CrmApplication.java` file.

### Method 2: Command Line (Requires Maven)
1. Install Maven (e.g., `choco install maven -y` if you have Chocolatey).
2. Run the following command in this directory:
   ```bash
   mvn spring-boot:run
   ```

## Features

- **Dashboard:** Overview of CRM metrics.
- **Customers:** Manage customer data and revenue.
- **Leads:** Track potential sales and sources.
- **Tasks:** Set reminders and priorities.
- **Auth:** Secure login and registration.
- **Export:** Export data to Excel/PDF (Admin only).
