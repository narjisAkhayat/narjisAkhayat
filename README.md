# Todo Task Manager

This is a simple Bash script for managing todo tasks. Each task has a unique identifier, a title, a description, a location, a due date and time, and a completion marker. The script allows you to create, update, delete, and list tasks, as well as search for tasks by title.

## Features

- **Create a Task**: Add a new task with a title, description, location, due date and time, and completion status.
- **Update a Task**: Modify an existing task's details.
- **Delete a Task**: Remove a task by its unique identifier.
- **Show Task Details**: Display all information about a specific task.
- **List Tasks by Date**: List completed and uncompleted tasks for a given day.
- **Search for Tasks**: Find tasks by their title.
- **Show Today's Tasks**: Display completed and uncompleted tasks for the current day when no arguments are provided.

## Getting Started

### Prerequisites

- Bash (version 4.0 or higher)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/todo-task-manager.git
    cd todo-task-manager
    ```

2. Make the script executable:
    ```sh
    chmod +x todo.sh
    ```

3. Create an initial `tasks.txt` file (optional, if you want to start with predefined tasks):
    ```sh
    echo -e "1652947200000000000|Finish homework|Complete math exercises|Home|2023-06-01 17:00|false\n1653033600000000000|Grocery shopping|Buy groceries for the week|Supermarket|2023-06-02 10:00|true\n1653120000000000000|Team meeting|Discuss project updates|Office|2023-06-03 14:00|false\n1653206400000000000|Dentist appointment|Regular check-up|Dental Clinic|2023-06-04 09:00|true\n1653292800000000000|Read book|Finish reading 'The Great Gatsby'|Home|2023-06-05 20:00|false" > tasks.txt
    ```

## Usage

Run the script with the desired action:

- **Create a Task**:
    ```sh
    ./todo.sh create
    ```

- **Update a Task**:
    ```sh
    ./todo.sh update
    ```

- **Delete a Task**:
    ```sh
    ./todo.sh delete
    ```

- **Show Task Details**:
    ```sh
    ./todo.sh show
    ```

- **List Tasks by Date**:
    ```sh
    ./todo.sh list
    ```

- **Search for Tasks**:
    ```sh
    ./todo.sh search
    ```

- **Show Today's Tasks**:
    ```sh
    ./todo.sh
    ```

## Task Format

Tasks are stored in `tasks.txt` with the following format:

