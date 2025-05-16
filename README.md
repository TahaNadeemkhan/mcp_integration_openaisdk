# Leave Management System

This is a simple Leave Management System built with `FastMCP`.

## Features

* **Check Leave Balance:** Check the remaining leave days for an employee.
* **Apply for Leave:** Apply for leave for specific dates.
* **Get Leave History:** View the leave history for an employee.
* **Personalized Greeting:** Get a personalized greeting.

## How to Use

The system is built using `FastMCP`. You can interact with it using the defined tools and resources.

### Tools:

* `get_leave_balance(employee_id: str)`: Use this tool to check the leave balance of an employee by providing their employee ID.
* `apply_leave(employee_id: str, leave_dates: List[str])`: Use this tool to apply for leave for an employee. You need to provide the employee ID and a list of leave dates in the format `["YYYY-MM-DD"]`.
* `get_leave_history(employee_id: str)`: Use this tool to get the leave history of an employee by providing their employee ID.

### Resources:

* `greeting://{name}`: Access this resource to get a personalized greeting by providing a name in the URL path.

To run the application, execute the `main.py` file. The `FastMCP` server will start, and you can then interact with it via its defined interface.