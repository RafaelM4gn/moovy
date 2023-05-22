# Moovy

Moovy is a web application that allows users to search for, save, and review their favorite movies.

## Prerequisites

You need to have Node.js, pnpm, and PostgreSQL installed on your machine.

## Database Setup

Before running the server, you need to set up the PostgreSQL database:

1. Create a new PostgreSQL database named `moovydb`.
2. Update the database connection settings in the `app.module.ts` file in the server directory.

## Setup & Running

### Server

1. Navigate to the server directory:
    ```
    cd server
    ```
2. Install the dependencies:
    ```
    pnpm install
    ```
3. Start the server:
    ```
    pnpm run start
    ```

The server should now be running on `http://localhost:3000`.

### Frontend

1. Navigate to the frontend directory:
    ```
    cd frontend
    ```
2. Install the dependencies:
    ```
    pnpm install
    ```
3. Start the application:
    ```
    pnpm run dev
    ```

The application should now be running on `http://localhost:5173`.

### OpenAPI

You can view the OpenAPI documentation for the server by navigating to `http://localhost:3000/api`.

