
**Flet To-Do App**

This README provides an overview of a To-Do App built using Flet, a Python framework for creating user interfaces for web, desktop, and mobile.

**Features:**

- **Create and manage tasks:** Add, complete, and delete tasks from your list.
- **Strikethrough for completed tasks:** Completed tasks are visually distinguished with a strikethrough line.
- **Dark/Light theme:** Switch between dark and light themes for better readability.
- **Responsive UI:** Adapts to different screen sizes and devices.

**Requirements:**

- Python (version 3.6 or later recommended)
- Flet ([https://flet.dev/](https://flet.dev/))

**Installation:**

1. Install Python if you haven't already: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
2. Install Flet using pip:

   ```bash
   pip install flet
   ```

**Running the App:**

1. Open a terminal or command prompt.
2. Navigate to the directory containing this code.
3. Run the following command:

   ```bash
   python to_do_app.py
   ```

This will launch the To-Do App in your web browser.

**How to Use:**

1. Enter your task description in the input field.
2. Click the "Add Task" button to add the task to your list.
3. Click the checkbox next to a task to mark it as completed.
4. Click the "Delete" icon next to a task to remove it from the list.
5. Click the toggle button in the top-right corner to switch between dark and light themes.

**Code Structure:**

- `to_do_app.py`: The main Python file containing the code for the entire application.
  - `flet` imports the Flet framework.
  - The code defines two main classes:
    - `ToDoItem`: Represents a single to-do item in the list.
    - `Hero`: The main content area of the app, handling task management, UI elements, and theme switching.
  - `main` function creates a `Hero` object and adds it to the Flet page.

**Additional Notes:**

- This code utilizes Flet's built-in styling capabilities through dictionaries and the `ft.Theme` object.
- The code effectively manages theme changes by updating the appearance of both newly added and existing to-do items.

**Feel free to customize the app further by:**

- Modifying the initial theme (set in `main`).
- Adding features like task editing or priority levels.
- Exploring Flet's extensive documentation and examples for more advanced customization ([https://flet.dev/](https://flet.dev/)).

**Contributing:**

If you find this code useful or have suggestions for improvement, feel free to fork the repository and submit a pull request.

I hope this README provides a clear and informative guide for using this To-Do App!
