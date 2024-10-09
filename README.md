# EMS

Employee Management System
This project is an Employee Management System built using Java and Swing for the graphical user interface. The system allows users to manage employee records, including adding, viewing, updating, and removing employee details.

Project Structure:
Employee-Management-System/
├── build/
│   ├── classes/
│   │   ├── .netbeans_automatic_build
│   │   └── .netbeans_update_resources
│   ├── build.xml
│   └── manifest.mf
├── nbproject/
│   ├── build-impl.xml
│   ├── genfiles.properties
│   ├── private/
│   │   ├── private.properties
│   │   └── private.xml
│   ├── project.properties
│   └── project.xml
├── src/
│   ├── employee/
│   │   ├── management/
│   │   │   ├── system/
│   │   │   │   ├── AddEmployee.java
│   │   │   │   ├── Conn.java
│   │   │   │   ├── Home.java
│   │   │   │   ├── Login.java
│   │   │   │   ├── RemoveEmployee.java
│   │   │   │   ├── Splash.java
│   │   │   │   ├── UpdateEmployee.java
│   │   │   │   └── ViewEmployee.java
│   ├── icons/


Main Components
# 1.AddEmployee.java:

Allows users to add new employee details.
Fields include name, father's name, address, phone, Aadhar number, email, salary, designation, and date of birth.

# 2.ViewEmployee.java:

Allows users to view employee details in a table format.
Provides search functionality to filter employees by their ID.
Includes options to print, update, or go back to the home screen.

# 3.UpdateEmployee.java:

Allows users to update existing employee details.
Triggered from the ViewEmployee class when the update button is clicked.

# 4.Home.java:

The main dashboard of the application.
Provides buttons to navigate to add, view, update, or remove employee screens.

# 5.Conn.java:

Manages database connections and queries.
Used by various classes to interact with the database.

# Database Interaction
The application uses JDBC to connect to a database and execute SQL queries.
The Conn class handles the database connection and query execution.
Employee data is stored in a table named employee.

# User Interface
The application uses Java Swing for the graphical user interface.
Various Swing components like JFrame, JLabel, JTextField, JButton, JTable, and JScrollPane are used to create the UI.
The UI is designed to be user-friendly with clear labels and buttons for each action.

# How to Run
The main entry point for the application is the Home class.
To start the application, run the main method in the Home class.

# Example Usage
1.Add Employee: Navigate to the add employee screen, fill in the details, and click the add button.

2.View Employees: Navigate to the view employees screen to see a list of all employees. Use the search functionality to filter by employee ID.

3.Update Employee: From the view employees screen, select an employee and click the update button to modify their details.

4.Remove Employee: Navigate to the remove employee screen to delete an employee record.
