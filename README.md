# Task Trek

Task Trek is a task management application built with React. It allows users to create tasks, assign tags, drag-and-drop tasks between different states (Todo, Doing, Done), and manage them with a simple and intuitive interface.

## Features

- **Task Creation**: Add new tasks with a title, status, and tags (e.g., HTML, CSS, JavaScript, React).
- **Drag-and-Drop**: Drag tasks between "Todo", "Doing", and "Done" columns.
- **Task Deletion**: Delete tasks with a single click.
- **Persistent Storage**: Tasks are saved to `localStorage`, ensuring they persist across page reloads.

## Installation

Follow these steps to get the project up and running locally:

### 1. Clone the repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/task-trek.git
cd task-trek
```

### 2. Install Dependencies

Install the project dependencies using npm or yarn:

```bash
npm install
```

or

```bash
yarn install
```

### 3. Run the Application

To start the development server and view the app in your browser, run:

```bash
npm start
```

or

```bash
yarn start
```

This will open the app at `http://localhost:3000` in your browser.

## Project Structure

Here is an overview of the project's file structure:

```
src/
│
├── components/
│   ├── TaskFrom/
│   │   └── TaskForm.jsx
|       └── TaskForm.css
│   ├── TaskColumn/
│   │   └── TaskColumn.jsx
|       └── TaskColumn.css
│   ├── TaskCard/
│   │   └── TaskCard.jsx
|       └── TaskCard.css
│   ├── Tag/
│   │   └── Tag.jsx
|       └── Tag.css
│   ├── DropArea/
│   │   └── DropArea.jsx
|       └── DropArea.css
│
├── assets/
│   ├── check-mark-button.png
│   ├── glowing-star.png
│   └── direct-hit.png
│
├── App.jsx
├── App.css
├── index.js
└── index.css
```

## How It Works

1. **TaskForm**: A form component for creating new tasks. Users can input a task title, select tags, and choose a status (Todo, Doing, or Done).
2. **TaskColumn**: A column component that represents each of the task categories (Todo, Doing, Done). Tasks are filtered based on their status and displayed accordingly.
3. **TaskCard**: Represents an individual task. Each card displays the task's title and tags, with a drag-and-drop functionality to reorder tasks.
4. **DropArea**: A component that provides the drop zone for dragging and dropping tasks.
5. **Tag**: A component for selecting tags for each task (HTML, CSS, JavaScript, React).

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **CSS**: Styling the app's components.
- **localStorage**: For saving tasks in the browser's local storage to persist across sessions.

## Contributing

We welcome contributions to Task Trek! To get started, fork the repository and submit a pull request with your changes. Here's how you can contribute:

1. Fork the repo.
2. Clone your fork: `git clone https://github.com/yourusername/task-trek.git`
3. Create a new branch: `git checkout -b my-branch`
4. Make your changes.
5. Commit your changes: `git commit -am 'Added new feature'`
6. Push to the branch: `git push origin my-branch`
7. Open a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- **React**: A declarative, efficient, and flexible JavaScript library for building user interfaces.
- **React Drag-and-Drop**: For implementing drag-and-drop functionality.
