# StaffHub

A Java-based desktop application for managing employee records, built with Swing and designed for use with MySQL.

## Features
- Add, view, update, and delete employee records
- Search and filter employees
- Print employee details
- User-friendly graphical interface

## Requirements
- **Java 17 JDK**
- **Apache Ant** (for building and running)
- **MySQL Server**
- **Required Libraries:**
  - `mysql-connector-java-8.0.28.jar`
  - `jcalendar-tz-1.3.3-4.jar`
  - `rs2xml.jar`

## Setup Instructions
1. **Install Java 17 JDK**
2. **Install Apache Ant**
3. **Install MySQL and create a database for employee records**
4. **Download required JARs** and place them in a `lib` folder or update their paths in `nbproject/project.properties`
5. **Configure database connection** in the source code if needed

## Build and Run
Open a terminal in the project directory and run:
```bash
ant clean
ant build
ant run
```
Or use your preferred IDE (NetBeans, IntelliJ IDEA, VS Code) to build and run the main class:
`employee.management.system.EmployeeManagementSystem`

## Project Structure
- `src/employee/management/system/` - Source code
- `src/icons/` - UI icons
- `build.xml` - Ant build script
- `nbproject/` - NetBeans project files

## License
This project is for educational purposes.