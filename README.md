# Todo Management Application

This is a React-based Todo Management Application that allows users to manage their tasks efficiently. Users can add, edit, mark as completed, and delete todos. The application stores todos in the local storage, ensuring persistence across sessions.

## Features

- Add new todos.
- Edit existing todos.
- Mark todos as completed or incomplete.
- Delete todos.
- Persistent storage using local storage.
- Dynamic and responsive user interface.

## Installation

1. Clone this repository:
  
2. Navigate to the project directory:
   ```bash
   cd todo-management-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Project Structure

```
src/
├── components/
│   ├── TodoForm.js     # Component for adding todos
│   ├── TodoItem.js     # Component for displaying individual todos
├── context/
│   ├── TodoContext.js  # Context provider for managing todos
├── pages/
│   ├── Dashboard.js    # Dashboard page
├── App.css             # Styling for the application
├── App.js              # Main application component
├── index.js            # Application entry point
```

## Usage

1. **Add a Todo**: Enter your task in the input field and click the `Add` button.
2. **Edit a Todo**: Click the edit icon (✏️), modify the text, and save changes by clicking the save icon (📁).
3. **Mark as Completed**: Check the checkbox next to a todo to mark it as completed.
4. **Delete a Todo**: Click the delete button (❌) to remove a todo.

## Technologies Used

- **Frontend**: React, TailwindCSS
- **State Management**: React Context API
- **Storage**: Local Storage

## Future Enhancements

- Add user authentication for personalized todo management.
- Implement filters for viewing completed and pending tasks.
- Integrate with a backend for cloud-based storage.

---
I’m a beginner coder on a mission to create and learn. Your feedback means a lot!  
Contact me at: [derkaran@gmail.com](mailto:derkaran@gmail.com)  
Connect with me on LinkedIn: [![LinkedIn](https://img.shields.io/badge/LinkedIn-Karan%20Der-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/karan-der/)

