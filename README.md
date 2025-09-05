Contact Vault Pro - A Console-Based Contact Management System
Welcome to Contact Vault Pro, a robust and feature-rich contact management application built entirely in Java. This project, created by Sarvesh Soumil, demonstrates core Java principles and Object-Oriented Programming (OOP) concepts in a practical, real-world utility. It provides a complete, user-friendly experience for managing contacts directly from the command-line interface (CLI).

✨ Features
Contact Vault Pro is more than just a simple list. It's a complete CRUD (Create, Read, Update, Delete) application with a focus on user experience and data integrity.

Add New Contacts: Easily create and add new contacts with their name, phone number, and email address.

View All Contacts: Display a clean, numbered list of all contacts currently stored in the system.

Edit Existing Contacts: A dedicated menu allows you to select a contact and modify their name, phone, or email individually.

Search Functionality: Quickly find a contact by searching for their name (case-insensitive).

Delete Contacts: Safely remove a contact from the list by selecting their corresponding number.

Duplicate Prevention: The system automatically checks for and prevents the entry of duplicate phone numbers, ensuring data integrity.

Input Validation:

Phone: Ensures that phone numbers contain digits.

Email: Validates that email addresses contain the "@" and "." characters for correct formatting.

Colorful & Interactive UI: The console interface is enhanced with ANSI color codes to provide a more dynamic, readable, and engaging user experience. Menus, prompts, success messages, and errors are all color-coded for clarity.

🛠️ How to Run the Project
To compile and run this project from the command line, ensure you have a Java Development Kit (JDK) installed.

Download the Files:

Contact.java

ContactManager.java

Open a Terminal or Command Prompt:
Navigate to the directory where you saved the two .java files.

Compile the Code:
Run the javac compiler. This will create .class files.

javac Contact.java ContactManager.java

Run the Application:
Execute the main class, ContactManager.

java ContactManager

The application will then launch in your terminal.

🏗️ Project Structure
This project follows Object-Oriented principles by separating concerns into two distinct classes:

Contact.java: This class acts as a blueprint (model) for a single contact object. It contains private fields for name, phoneNumber, and email, along with constructors, getters, and setters to manage this data.

ContactManager.java: This is the main driver class that contains the application logic (main method). It handles user input, manages the ArrayList of Contact objects, and contains all the methods for the application's features.

This separation makes the code cleaner, more organized, and easier to maintain or extend in the future.

🚀 Future Enhancements
Data Persistence: Implement file I/O to save contacts to a .csv or .txt file, so the data persists even after the application is closed.

Sorting: Add the ability to sort and view contacts alphabetically by name.

Contact Groups: Allow users to assign contacts to groups like "Family," "Work," or "Friends."

✍️ Author
Sarvesh Soumil
