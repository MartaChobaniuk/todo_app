## [DEMO LINK](https://martachobaniuk.github.io/todo_app/)

# To-Do App

The To-Do App is a simple and efficient task management application built with React and TypeScript. It allows users to create, edit, and delete tasks, helping them stay organized and productive.

## Technologies Used

- **React**: Frontend framework for building the UI.
- **TypeScript**: Ensures type safety and better maintainability..
- **SCSS**: Provides styling with modular and reusable styles.
- **Classnames**: Helps manage dynamic class names.

## Folder Structure

- `index.html`: Main HTML file
- `/styles`: Contains the SCSS source files
- `/сomponents`: Contains React components such as Header, TodoList, Footer, etc.
- `/types`: Defines TypeScript types and interfaces.
- `/utils`: Contains utility functions like getTodoFilter and fetchClient.
- `/api`: Handles API interactions for fetching, adding, and deleting todos.

## Features

- **Clean and Maintainable Code**: Utilizes modular React components and TypeScript.
- **Adaptive Layout**: Ensures usability across various devices.
- **Task Management**:  Add, edit, delete, and mark tasks as completed.
- **Error Handling**: Displays notifications when API calls fail.

## Commands

| Name    | Command         |
| ------- | --------------- |
| Install | `npm install`   |
| Start   | `npm run start` |
| Build   | `npm run build` |

## App Logic Overview

- Users can add new tasks by entering a task name and submitting it.
- Tasks can be marked as completed, edited, or deleted.
- The application interacts with an API to fetch, add, update, and delete todos.
- Error messages are displayed when API interactions fail.
- A clear button allows users to remove all completed tasks at once.
