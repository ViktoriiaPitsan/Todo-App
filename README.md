# React Todo App with API

## Project Description
This is a simple Todo App built with React, TypeScript, and integrates with an external API for managing todos. The app allows users to load, add, delete, toggle, and rename todos. All changes are saved to the API to persist data.

### Purpose:
The main goal of this project is to learn how to work with React, TypeScript, and APIs. The app follows best practices for managing state, handling API requests, and providing feedback to the user.

## Live Preview
[Live Demo](https://ViktoriiaPitsan.github.io/Todo-App/)

## Technologies Used
- **React** - JavaScript library for building user interfaces
- **TypeScript** - Typed superset of JavaScript
- **Vite** - Next-generation, fast build tool
- **Sass** - CSS preprocessor for enhanced styling
- **Fetch** - For making HTTP requests to the API.

## Features

- **Load Todos**: Fetch todos from the API and display them in the app. This feature allows users to view their existing todos, which are fetched from an external API.

- **Add Todo**: Add a new todo to the list with validation. When a new todo is added, a POST request is sent to the API to save it. The title is validated to ensure it is not empty, and the input field is cleared upon successful addition.

- **Delete Todo**: Remove a todo from the list with API integration. When a todo is deleted, a DELETE request is made to the API, and the todo is removed from the list. Error handling is in place to show a notification if the deletion fails.

- **Toggle Todo Status**: Mark todos as completed or pending by toggling their status. A PUT request is sent to the API to update the status of the todo, and the change is immediately reflected in the UI.

- **Rename Todo**: Edit the title of a todo. The user can double-click a todo's title to enter edit mode, make changes, and submit them. A PUT request is sent to the API to update the title, and the UI is updated accordingly.


## Getting Started

### Clone the repository:
To get started with the project, first clone the repository:

git clone https://github.com/your-username/todo-app.git
cd todo-app

### Install dependencies:
npm install
# or
yarn install

### Run the project locally:
npm start
# or
yarn start



