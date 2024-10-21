# Student Management Application

## Overview
The Student Management Application is a Java console-based application designed to manage student records efficiently. It allows users to capture new student details, search for students by their unique ID, delete student records, and generate reports of all students.

## Features
- **Capture New Student**: Add new student records with ID, name, age, email, and course.
- **Search for Student**: Find a student using their unique ID and view their details.
- **Delete Student**: Remove a student record from the system based on the student ID.
- **Print Student Report**: Generate and display a report of all students.
- **Exit Application**: Safely terminate the application with a farewell message.

## Prerequisites
- Java Development Kit (JDK) 8 or higher.
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or a terminal for compilation and execution.

## Setup

### Running the Application
1. **Clone the Repository** (if applicable):
   ```bash
   git clone https://github.com/HChristopherNaoyuki/student-management-app-demo.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd student-management
   ```

3. **Compile the Java Files**:
   ```bash
   javac Solutions/*.java
   ```

4. **Run the Application**:
   ```bash
   java Solutions.StudentManagementApplication
   ```

## Code Structure

### Classes
- **Student**: Represents a student's record with attributes for ID, name, age, email, and course. It provides methods for saving, searching, deleting, and generating reports for student records.

- **StudentManagementApplication**: Contains the main method and provides a console interface for interacting with the student management features. It includes a menu-driven system to guide user actions.

- **StudentTest**: Contains unit tests for the `Student` class using JUnit 4 to ensure the correctness of various functionalities such as saving, searching, and deleting student records.

## Usage
1. Upon starting the application, users will see a welcome message and a prompt to launch the menu.
2. Users can select an option from the menu to capture new students, search for students, delete records, print reports, or exit the application.
3. Input the requested information as prompted by the console.

### Example Flow
- To capture a new student, select option (1), enter the student ID, name, age (must be 16 or older), email, and course.
- To search for a student, select option (2) and enter the student ID to retrieve their details.
- To delete a student, select option (3) and confirm the action.
- To print a report, select option (4), which will display all stored student records.

## Testing
The application includes a `StudentTest` class with unit tests for critical functionality:
- Ensure that students can be added, retrieved, and deleted correctly.
- Validate student age input to confirm that it meets the specified requirements.

### Running Tests
1. Ensure that JUnit is added to your project.
2. Run the tests using your IDE or from the command line.
