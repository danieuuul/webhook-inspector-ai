# API Project

## 📂 Project Structure

The project is organized as follows:

- **src/**: Contains the source code of the API.
  - **controllers/**: Handles the business logic for each route.
  - **models/**: Defines the data models and database schemas.
  - **routes/**: Contains the route definitions for the API.
  - **services/**: Includes reusable services and utilities.
  - **config/**: Configuration files (e.g., database, environment variables).
- **tests/**: Contains unit and integration tests.
- **package.json**: Manages dependencies and scripts.

## 🛠️ Technologies

The API is built using the following technologies:

- **Node.js**: JavaScript runtime for building the backend.
- **Express.js**: Web framework for handling routes and middleware.
- **TypeScript**: Superset of JavaScript for type safety.
- **MongoDB**: NoSQL database for data storage.
- **Mongoose**: ODM library for MongoDB.
- **Jest**: Testing framework for unit and integration tests.
- **dotenv**: For managing environment variables.

## 🚀 Getting Started

Follow these steps to run the project locally:

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v16 or higher)
- **npm** (Node Package Manager)
- **MongoDB** (running locally or a connection URI)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/webhook-inspector-ai/api.git
   cd api
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and configure the following variables:
   ```env
   PORT=3000
   MONGO_URI=mongodb://localhost:27017/your-database
   ```

### Running the API

1. Start the development server:

   ```bash
   npm run dev
   ```

2. The API will be available at `http://localhost:3000`.

### Testing

Run the test suite:

```bash
npm test
```

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
