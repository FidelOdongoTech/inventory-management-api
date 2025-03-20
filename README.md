# Inventory Management API

This is a simple **Inventory Management API** built using **Node.js**, **Express**, and **PostgreSQL**, and deployed with **Docker**.

## Features

- Stores inventory items with name and quantity.
- Provides an API endpoint to fetch all inventory items.
- Uses **PostgreSQL** as the database.
- Runs inside **Docker** containers for easy setup.

## Project Structure

## Getting Started

### 1. Clone the Repository

### 2. Set Up Environment Variables

Create a `.env` file in the project root and add:

### 3. Run the Project with Docker

Ensure **Docker** and **Docker Compose** are installed, then run:

This will start the **PostgreSQL database** and **backend server** inside Docker containers.

### 4. Verify the API

Once running, test the API:

Expected response:

### 5. Stopping the Containers

To stop the running containers, press `Ctrl + C` or run:

## API Endpoints

| Method | Endpoint | Description               |
| ------ | -------- | ------------------------- |
| GET    | `/items` | Fetch all inventory items |

## Contributing

Feel free to fork the repository and submit pull requests

## License

This project is open-source and available under the **MIT License**

