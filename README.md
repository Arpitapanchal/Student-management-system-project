# Student-management-system-project
 Student  Management System  is a management information system for education sector establishments used to manage student data. It integrates students, parents, teachers and the administration. This project is a desktop application designed using Python and the Tkinter library. This application allows users to perform various CRUD (Create, Read, Update, Delete) operations on student records within a graphical user interface (GUI). It uses SQLite3 as the database to store student information securely and efficiently.

Technical Description:

The application starts by importing the necessary libraries: tkinter for GUI creation, tkinter.ttk for advanced widgets, tkinter.messagebox for pop-up messages, and sqlite3 for database operations. The Database function initializes the connection to the SQLite database and creates a table named STUD_REGISTRATION if it does not exist. This table stores student information such as ID, name, contact, email, roll number, and branch.

The DisplayForm function sets up the GUI layout. It creates the main window with specific dimensions and title, and defines global variables for the form fields and the search functionality. The layout is divided into frames: the top frame for the heading, the left frames for the registration form and search options, and the middle frame for displaying student records.

The registration form includes input fields for the student's name, contact, email, roll number, and branch, along with a submit button that calls the register function. This function validates the input data, inserts it into the database, and displays a success message.

The search functionality allows users to search for student records by name. The search results are displayed in a tree view widget, which is a tabular representation of the records. The SearchRecord function handles the search operation by querying the database with the entered search term.

The application also includes buttons for viewing all records, resetting the form, and deleting selected records. The DisplayData function retrieves and displays all student records from the database in the tree view. The Reset function clears the current data and form fields, while the Delete function removes the selected record from the database after user confirmation.

Scrollbars are added to the tree view to handle large data sets, ensuring a smooth user experience. The tree view columns are configured with appropriate headings and widths to display the student information clearly.

Finally, the DisplayForm function is called to create and display the GUI, and the mainloop function runs the application, keeping the window open until the user closes it.

General Description:

This project is a user-friendly application designed to manage student information efficiently. Users can add new student records, view existing records, search for specific students by name, and delete records if necessary. The application ensures data integrity by validating inputs and confirming deletions. The graphical interface is intuitive and easy to navigate, making it suitable for users with varying levels of technical expertise.

By integrating a robust database with a clean and functional GUI, this Student Management System serves as an excellent tool for educational institutions or any organization that needs to maintain detailed records of students or members. The use of Tkinter for the GUI and SQLite3 for the database ensures that the application is lightweight, portable, and reliable.













