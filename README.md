# Hospital-Management-Project-using-C
The Hospital Management System (HMS) is a simple console-based application developed using C++. The main purpose of this project is to digitally organize and manage hospital records in an efficient and structured manner. The system focuses on handling two important entities within a hospital — Patients and Staff Members. It allows the user to add new records, store them temporarily, and display them whenever required.

This project is built by applying key Object-Oriented Programming (OOP) principles. A base class named Person is used to represent common attributes such as ID and Name. The classes Patient and Staff are derived from the base class and contain additional information like Illness for patients and Role for staff. This use of inheritance ensures code reusability and a clean structure. The concept of polymorphism is demonstrated through the display() function, which works differently for patients and staff, depending on the object type calling it.

The system is menu-driven, making it user-friendly and easy to operate. Users can repeatedly choose between different options such as adding or viewing patient and staff records until they choose to exit. Arrays are used to store multiple entries during program execution.

Although the current version handles basic data storage temporarily in memory, the program provides a strong foundation for further improvements such as file handling, appointment scheduling, billing management, and database integration in future versions.

Overall, this project reflects a practical implementation of OOP concepts and serves as a stepping stone toward creating advanced management systems for real-world applications.
