# Grocery App - Client

This directory contains the frontend code for the Grocery App, built with React and Vite.

## Getting Started

### Prerequisites

- Node.js and npm (or yarn) should be installed on your system.

### Installation

1.  Navigate to the `client` directory:
    ```bash
    cd client
    ```
2.  Install the dependencies:
    ```bash
    npm install
    ```

### Running the Development Server

To start the local development server, run the following command:

```bash
npm run dev
```

The application will be accessible at `http://localhost:5173` (or another port if 5173 is busy).

## Project Structure

-   `public/`: Contains static assets like `favicon.svg` that are not processed by Vite.
-   `src/`: Contains the main source code for the React application.
    -   `assets/`: Static assets like images and icons that are imported into components.
    -   `components/`: Reusable React components used throughout the application (e.g., `Navbar`, `Footer`, `ProductCard`).
    -   `context/`: Contains React context providers for state management (e.g., `AppContext`).
    -   `pages/`: Components that represent the different pages of the application (e.g., `Home`, `Cart`, `Login`).
    -   `App.jsx`: The root component of the application, which handles routing.
    -   `main.jsx`: The entry point of the aplication where the React app is mounted to the DOM.
-   `index.html`: The main HTML template for the application.
-   `vite.config.js`: Configuration file for the Vite build tool.
-   `package.json`: Defines project metadata and dependencies.