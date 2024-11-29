# Kanban Board Application

This is a Kanban board application built using React JS that interacts with the provided API from https://api.quicksell.co/v1/internal/frontend-assignment. The application allows users to dynamically adjust the Kanban board based on their grouping and sorting preferences. Users can group tickets by status, user, or priority, and sort the displayed tickets by priority or title. The application also retains the user's view state even after page reload.

## Features

- Group tickets by status, user, or priority.
- Sort tickets by priority or title.
- Visually appealing and responsive design.
- Ability to save the user's view state in local storage.
- Priority levels are defined as Urgent (4), High (3), Medium (2), Low (1), and No priority (0).

## Project Structure

* **.gitignore** 
Specifies files and directories that should be ignored by Git.

*  **package.json**
Contains metadata about the project and its dependencies.

*  **public/index.html**
The main HTML file that serves as the entry point for the React application.

*  **public/manifest.json**
Provides metadata used when the web app is installed on a user's device.

*  **public/robots.txt**
Instructs web crawlers on how to index the website.

*  **src/App.css**
Contains the global styles for the application.

*  **src/App.js**
The main React component that sets up the application's structure and routes.

*  **src/App.test.js**
Contains tests for the App component.

*  **src/Assets/Images/**
Directory for storing image assets used in the application.

*  **src/Components/Card/Card.css**
Contains styles specific to the Card component.

*  **src/Components/Card/Card.js**
Defines the Card component, which represents individual tickets on the Kanban board.

*  **src/Components/List/List.css**
Contains styles specific to the List component.

*  **src/Components/List/List.js**
Defines the List component, which displays a list of tickets based on grouping and ordering preferences.

*  **src/Components/Navbar/Navbar.css**
Contains styles specific to the Navbar component.

*  **src/Components/Navbar/Navbar.js**
Defines the Navbar component, which provides options for grouping and ordering tickets.

*  **src/index.css**
Contains global styles for the application.

*  **src/index.js**
The entry point for the React application, rendering the App component into the DOM.

*  **src/reportWebVitals.js**
Measures and reports on the performance of the application.

*  **src/setupTests.js**
Configures the testing environment for the application.

*  **README.md**
Provides an overview of the project, its features, and instructions for setup and usage.


## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```shell
   git clone https://github.com/riyasingh99/kanban-board.git
   ```
2. Navigate to the project directory:
    ```shell
    cd kanban-board
    ```
3. Install the dependencies:
    ```shell
    npm install
    ```
### Running the Application
* To start the development server, run:
    ```shell
    npm start
    ```
### Building the Application
* To create a production build, run:
    ```shell
    npm run build
    ```
### Running Tests
* To create a production build, run:
    ```shell
    npm test
    ```
 ### Link To Live Project
 ```shell 
 https://riyasingh99.github.io/kanban-board/
 ```
