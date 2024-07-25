# Student-management-system-project
 Student  Management System  is a management information system for education sector establishments used to manage student data. It integrates students, parents, teachers and the administration. 
This is a Python application built using the Tkinter library for GUI development and SQLite for database management. The project aims to facilitate the management of student records, including their registration, search, display, and deletion.

The application starts by importing the necessary libraries: Tkinter for the graphical user interface and SQLite for database operations. The Database function establishes a connection to an SQLite database named student.db and creates a table STUD_REGISTRATION if it doesn't already exist. This table stores student information such as ID, name, contact, email, roll number, and branch.

The DisplayForm function sets up the GUI layout. It creates a main window with specified dimensions and a title. Inside the window, various frames are created for different sections: a top frame for the heading, a left frame for the registration form, another left frame for search functionality, and a mid frame for displaying student records in a table format. The registration form allows users to enter student details through labeled entry fields and a submit button.

Search functionality is implemented with an entry field and a search button that filters student records by name. Additional buttons for viewing all records, resetting the form, and deleting selected records are provided. The main display area uses a Treeview widget from the ttk module, which supports horizontal and vertical scrolling for better navigation of student records.

The register function handles the submission of new student records to the database. It validates that all fields are filled, inserts the data into the database, and updates the display. The Reset function clears the form and refreshes the data display, while the Delete function removes selected records after user confirmation.

The SearchRecord function filters and displays records based on the search query, and the DisplayData function fetches and displays all records from the database. The application is designed to be user-friendly, making it easy for users to manage student data efficiently.

The main loop of the Tkinter application (mainloop) runs the program, ensuring the GUI remains responsive to user interactions. This project demonstrates the integration of a GUI with a database to create a functional and interactive student management system.







