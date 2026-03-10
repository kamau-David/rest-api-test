# Node.js, Express & MongoDB Learning Project

Welcome! This project is designed to help you learn the fundamentals of building a REST API using Node.js, Express, and MongoDB.

## Project Structure

- `server.js`: The main entry point of the application.
- `config/`: Contains configuration files (e.g., database connection).
- `models/`: Defines the data schemas using Mongoose.
- `routes/`: Defines the API endpoints.
- `controllers/`: Contains the logic for handling requests.
- `.env`: Stores environment variables (Port, MongoDB URI).

## Getting Started

1.  **Install Dependencies:**

    ```bash
    npm install
    ```

2.  **Configure Environment Variables:**
    Edit the `.env` file and provide your MongoDB URI if it's different from the default.

3.  **Run the Server:**
    - Development mode (with nodemon):
      ```bash
      npm run dev
      ```
    - Production mode:
      ```bash
      npm start
      ```

## API Endpoints

### Products

- `GET /api/products`: Get all products.
- `POST /api/products`: Create a new product.
- `GET /api/products/:id`: Get a single product by ID.
- `PUT /api/products/:id`: Update a product by ID.
- `DELETE /api/products/:id`: Delete a product by ID.

## Learning Path

1.  Start by examining `server.js` to see how the Express app is initialized and how middleware is used.
2.  Look at `config/db.js` to understand how Mongoose connects to MongoDB.
3.  Check `models/Product.js` to see how to define a schema.
4.  Explore `controllers/productController.js` to learn how to interact with the database using Mongoose methods.
5.  See how `routes/productRoutes.js` maps HTTP methods to controller functions.
