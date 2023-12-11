![ezgif-3-3fd671ccc8](https://github.com/Snldmrtnz/Smart-Score/assets/118676134/02731d83-7708-4153-bab7-660f03c70770)

![🧑_🎓Smart_Score 🖥️ (1)](https://github.com/Snldmrtnz/Smart-Score/assets/118676134/9e1283f1-307b-491d-ad72-70f24ac55782)

# Introduction
## Project Introduction: SmartScore Student Management System

The SmartScore Student Management System is a robust and user-friendly application designed to streamline the management of student records. Developed using Python's Tkinter library for the graphical user interface (GUI) and integrated with a MySQL database, this project provides an efficient solution for educational institutions seeking to organize and manipulate student data seamlessly.

## Features
- Data Management: Add, update, delete, and search for student records.
- Grade Calculation: Automatically calculates the Grade Weighted Average (GWA) based on midterm and finals grades.
- Export to Excel: Export student data to an Excel file for easy sharing and analysis.

## Database Management
1. Imported Libraries:
   - csv: For reading and writing CSV files (though not used in the provided code).
   - tkinter: For creating the GUI.
   - datetime: For working with dates and times.
   - pymysql: For interacting with MySQL databases.
   - xlsxwriter: For creating Excel files.
2. Database Connection:
   - The connection function establishes a connection to a MySQL database named 'sms' running on 'localhost' with the 'root' user and no password.
3. Tkinter GUI:
   - A Tkinter window is created with the title "SmartScore" and a size of 820x640 pixels.
   - A Treeview widget (my_tree) is used to display data in tabular form.
4. Functions:
   - read: Executes a SELECT SQL query to retrieve data from the 'student_data' table and returns the results.
   - refreshTable: Clears the existing data in the Treeview and populates it with the latest data from the database.
   - setph: Sets values in the placeholderArray list based on the provided word and number.
   - Several functions (save_button_click, update_button_click, etc.) are defined to handle button clicks for actions like saving, updating, deleting, etc.
   - save: Inserts a new record into the 'student_data' table based on the values entered in the GUI.
   - update: Updates an existing record in the 'student_data' table based on the selected row in the Treeview.
   - delete: Deletes the selected record from the 'student_data' table.
   - select: Populates the entry fields in the GUI with the values of the selected row in the Treeview.
   - find: Executes a SELECT SQL query based on the entered criteria and populates the entry fields if a matching record is found.
   - clear: Clears all the entry fields in the GUI.
   - exportExcel: Exports the data from the 'student_data' table to an Excel file.
5. GUI Elements:
   - Entry widgets and Comboboxes for entering and selecting data.
   - Buttons for various actions such as saving, updating, deleting, etc.
   - Treeview widget for displaying data in a tabular format.
6. Styling:
   - The code includes some styling using colors and spacing.
7. Main Execution:
   - The script defines a main window, sets up the GUI elements, configures the Treeview columns, and populates the initial data in the Treeview using the refreshTable function.
   - The script enters the Tkinter event loop (window.mainloop()) to handle user interactions.
  
## Requirements
- Python 3.x
- Tkinter library
- MySQL database (adjust connection details in the code)

# How to Use
## 1. Run the Application:
 
  - Ensure you have Python installed.
  - Adjust the MySQL connection details in the code.
  - Run the script to launch the SmartScore application.
## 2. Manage Student Data:

  - Use the form to input or update student information.
  - Click on buttons like SAVE, UPDATE, DELETE, SELECT, FIND, CLEAR, and EXPORT EXCEL to perform respective actions.
## 3. Grade Calculation:

  - The system automatically calculates the GWA based on the entered midterm and finals grades.
## 4. Export Data:

  - Click the "EXPORT EXCEL" button to export student data to an Excel file.

# Dependencies
- Tkinter: GUI library for the application window.
- pymysql: Python MySQL database connector.
- xlsxwriter: Library for writing data and formatting information to Excel files.

# Note
- the code interacts with a MySQL database, and the structure of the 'student_data' table is assumed based on the SQL queries used in the code. The functionality provided by this code is a simple CRUD (Create, Read, Update, Delete) application for managing student data.
- This application is a basic example and might require further customization based on specific use cases.
- Ensure that the required libraries are installed (pymysql, xlsxwriter) before running the application.
- Feel free to contribute and enhance the SmartScore Student Management System!

# Video Presentation
https://drive.google.com/drive/folders/1EKclaM_Gs_gX9Kss1M9ZDq49Qd4-_5sL

# Group Members
- Carandang, Angelica
- Calalo, Homer
- Lecaroz, Diomael
- Hernandez, Edrian Clavillas
- Martinez, Sean Iliad L.
