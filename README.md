# Employee Management System using Python (File Handling)

This project is a basic Employee Management System implemented using Python, demonstrating file handling capabilities. It allows users to manage employee records, including adding new employees, viewing all employees, and searching for a specific employee by their ID. All employee data is stored in a text file, showcasing how file I/O operations can be utilized for basic data management.

## Features

- **Add Employee:** Add new employee records, including Employee ID, Name, Salary, and Department.
- **View Employees:** Display all employee records stored in the system with detailed information.
- **Search Employee:** Search for an employee by their Employee ID.
- **File Handling:** All employee records are stored in a text file (`employees.txt`) and are retrieved when needed.

## How It Works

1. **Adding Employees:**
   - The user can add one or multiple employees.
   - Each employee record consists of an Employee ID, Name, Salary, and Department.
   - The information is saved in the `employees.txt` file.

2. **Viewing Employees:**
   - The system reads the `employees.txt` file and displays all employee records.
   - If no records exist, the user will be informed that no employees are available.

3. **Searching for an Employee:**
   - The user can search for an employee using their unique Employee ID.
   - If the employee is found, their details (Name, Salary, and Department) are displayed.

## File Structure

- The employee records are stored in a text file (`employees.txt`) in the following format:
  ```
  EmployeeID, EmployeeName, EmployeeSalary, EmployeeDepartment
  ```

## Getting Started

### Prerequisites

- Python 3.x
- `colorama` module (to install, use `pip install colorama`)

### How to Run

1. Clone the repository or download the project files.
2. Make sure `colorama` is installed:
   ```bash
   pip install colorama
   ```
3. Run the `Employee Management System` program:
   ```bash
   python employee_management.py
   ```

4. Follow the on-screen prompts to manage employees:
   - Add employees
   - View all employees
   - Search for an employee

## Code Structure

- `Add()`: Allows the user to add new employee records.
- `Display()`: Displays all the employee records stored in the system.
- `Search()`: Searches for a specific employee using their Employee ID.
- `main()`: The main menu that runs the Employee Management System.

## Example

```
Employee Management System
1. Add Employee
2. View Employees
3. Search Employee
4. Exit
Enter your choice (1-4): 1

Enter how many employees you want to ADD>> 1
Enter Employee ID>> 101
Enter Employee Name>> John Doe
Enter Employee Salary>> 50000
Enter Employee Department>> HR
Employee added successfully!

...
```

## Future Enhancements

- Adding functionality to delete an employee record.
- Implementing file encryption for secure data storage.
- Improving the user interface with a graphical interface (GUI).

## Contributing

Feel free to contribute to this project by submitting pull requests. For major changes, please open an issue first to discuss what you would like to improve.

## License

This project is open-source and available under the [MIT License](LICENSE).
