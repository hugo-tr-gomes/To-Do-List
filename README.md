# TypeScript Console To-Do List Challenge

## Overview:

This challenge involves building a To-Do List application using TypeScript with a focus on console-based interaction. It spans two weeks, covering basic functionalities like adding, updating, and deleting tasks. The second week introduces advanced features such as data persistence and testing.

## Week 1: Basic Functionality

- **Task Class:**
  - Create a `Task` class with essential properties.
  
- **To-Do List Class:**
  - Manage tasks with methods for CRUD operations.

- **Console Display:**
  - Implement functions to display tasks in the console.

- **User Interaction:**
  - Use `readline-sync` for a simple command-line interface.

## Week 2: Advanced Features

- **Persistence:**
  - Save and load tasks from a JSON file.

- **Filtering and Sorting:**
  - Enhance the `TodoList` class to support filtering and sorting.

- **Error Handling:**
  - Implement error handling for user input and edge cases.

- **Testing:**
  - Write unit tests for classes and functions using Jest.

## Getting Started:

1. Clone the repository.
2. Install dependencies: `npm install`.
3. Run the application: `npm start`.

## Sample Console Outputs:

1. **Displaying Tasks:**
   ```
   Tasks:
   ID  | Description               | Completed
   -------------------------------------------
   1   | Buy groceries             | ✔
   2   | Complete TypeScript chal | ✖
   3   | Read a book               | ✔
   ```

2. **Adding a Task:**
   ```
   Enter task description: Study TypeScript
   Task added: Study TypeScript
   ```

3. **Updating a Task:**
   ```
   Enter task ID to update: 2
   Enter new task description: Finish TypeScript challenge
   Task updated: Finish TypeScript challenge
   ```

4. **Deleting a Task:**
   ```
   Enter task ID to delete: 3
   Task deleted: Read a book
   ```

5. **Toggling Task Status:**
   ```
   Enter task ID to toggle status: 1
   Task status toggled for: Buy groceries
   ```

6. **Invalid Choice:**
   ```
   Enter your choice: 7
   Invalid choice. Please try again.
   ```

Feel free to adapt and extend the challenge based on your preferences. Happy coding!

---
