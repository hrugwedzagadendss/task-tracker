# My React App

This is a **React + Vite** project for a simple Task Tracker application. It's a foundational setup that demonstrates a basic React component, state management, and the use of external libraries.

## Project Structure

The project contains two main parts: a **classic HTML/CSS/JS application** at the root and a **modern React application** within the `my-react-app` directory.

### Root Directory (`/`)

  * **`index.html`**: The main HTML file for a simple, non-React task tracker.
  * **`style.css`**: The stylesheet for the root `index.html`.
  * **`script.js`**: A basic JavaScript file that logs a message to the console.

-----

### React Application (`/my-react-app`)

This is a standard Vite-powered React project.

  * **`src/App.jsx`**: The main React component. It uses the `useState` hook to manage a simple counter and displays Vite and React logos.
  * **`src/main.jsx`**: The entry point for the React application, which renders the `<App />` component into the `index.html`.
  * **`index.html`**: The HTML file specifically for the React app. It has a `<div id="root"></div>` where the React components are mounted.
  * **`package.json`**: Lists the project's dependencies and development dependencies, including `react`, `react-dom`, and `@vitejs/plugin-react`. It also defines scripts for running and building the application.
  * **`vite.config.js`**: The configuration file for Vite, which is the build tool used to bundle the React application.
  * **`node_modules/`**: Contains all installed dependencies, including `react`, `react-dom`, and `react-icons`.

-----

## Getting Started

To get this project running locally, follow these steps:

1.  Navigate to the `my-react-app` directory in your terminal.
    ```sh
    cd my-react-app
    ```
2.  Install the dependencies.
    ```sh
    npm install
    ```
3.  Start the development server.
    ```sh
    npm run dev
    ```

The application will be available at the local URL provided in the terminal output (e.g., `http://localhost:5173`).

## Key Features

  * **React + Vite**: A modern and fast development environment for building web applications.
  * **State Management**: Uses React's built-in **`useState` hook** to manage the component's state, as seen in the `App.jsx` counter.
  * **Linting**: Configured with ESLint to ensure code quality and consistency using `@eslint/js`, `eslint-plugin-react-hooks`, and `eslint-plugin-react-refresh`.
  * **External Packages**: The project includes `react-icons`, a library that makes it easy to add customizable SVG icons to your React app.
