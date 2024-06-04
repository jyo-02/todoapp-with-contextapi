# Todo App with Contextapi

## Overview

This is a simple Todo application built with React, utilizing Context API for state management. It allows users to manage their tasks by adding, updating, deleting, and marking them as complete.

## Features

- Add new todos
- Update existing todos
- Delete todos
- Mark todos as complete/incomplete
- Local storage integration to persist todos between sessions

## Technologies Used

- React
- JavaScript
- HTML
- CSS

## Setup Instructions

To run this application locally, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone <repository_url>
    ```

2. Navigate to the project directory:

    ```bash
    cd your_project_directory
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm run dev
    ```



5. Open your browser and go to the corresponding localhost port to view the application.

## Usage

1. **Add Todo**: Enter a task in the input field and press Enter or click the Add button to add it to the list.

2. **Update Todo**: Click on the todo item to edit its content.

3. **Delete Todo**: Click on the delete button next to a todo item to remove it from the list.

4. **Mark as Complete/Incomplete**: Click on a todo item to toggle its completion status.

## Folder Structure

- `src/`: Contains the source code for the React application.
- `components/`: Contains reusable React components.
 - `TodoForm.js`: Component for adding new todos.
 - `TodoItem.js`: Component for displaying individual todo items.
- `context/`: Contains the context provider for managing todos.
 - `TodoContext.js`: Context provider for managing todos using Context API.
- `App.js`: Main component that renders the Todo application.
- `public/`: Contains static assets and the HTML template file.

## Context API Usage

Context API is used to manage the state of todos throughout the application. The `TodoContext.js` file provides a context provider that wraps the entire application, allowing any component within the application to access and modify the todos state.




