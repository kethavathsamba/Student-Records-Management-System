# Student Records Management System

## Overview
The **Student Records Management System** is a Python-based application that provides CRUD (Create, Read, Update, Delete) operations for managing student data stored in a JSON file. This project simplifies record handling by enabling operations like adding new students, listing all records, updating existing records, and deleting records, with the data persisted in a JSON file.

## Features
- **Add New Students**: Create new student records and store them in a JSON file.
- **List Students**: Display all stored student records.
- **Update Records**: Modify details of existing student records.
- **Delete Records**: Mark a record as deleted by updating its value.
- **Search Functionality (Under Development)**: Planned feature to search for students by class.

## Files
### 1. `studentRecords.json`
- This file is used to store all student records in JSON format.
- Automatically created if it does not exist.

### 2. `main_module.py`
- The main Python script containing the implementation of all CRUD operations.
- Key functions:
  - `student_create(student)`: Adds a new student record.
  - `student_list()`: Retrieves and displays all student records.
  - `student_update(roll_no, student)`: Updates the details of a student based on their roll number.
  - `student_delete(roll_no)`: Marks a record as deleted for a given roll number.
  - `class_search(class_no)`: (Currently under construction) A function intended to search for students in a specific class.
### 3. `gui.py`
  - python script containing the gui components and there properties.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-records-management.git
   cd student-records-management
   ```

2. Run the Python script:
   ```bash
   python gui.py
   ```

3. Use the provided functions in the script to perform CRUD operations.

## Future Enhancements
- Implement the `class_search` functionality to allow searching for students by class.
- Add a user-friendly command-line or GUI interface for easier interaction.
- Export data to various formats (e.g., CSV, TXT).

## Prerequisites
- Python 3.x installed on your system.

## How to Contribute
Feel free to fork the repository and contribute to this project by:
- Fixing bugs.
- Adding new features.
- Improving the code structure.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

