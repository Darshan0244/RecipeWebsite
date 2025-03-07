# Recipe Website

This is a full-stack recipe-sharing website built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The website allows users to create, share, and browse recipes.

## Features

- **Recipe Management:** Users can create, edit, and delete their own recipes.
- **Recipe Search:** Browse through recipes using search functionality.
- **User Authentication:** Users can register, log in, and manage their accounts.
- **Recipe Categories:** Recipes can be categorized by cuisine, type, etc.
- **Favorites:** Users can save their favorite recipes for easy access.

## Tech Stack

- **Frontend:**
  - React.js (with React Router for navigation)
  - CSS for styling
- **Backend:**
  - Node.js
  - Express.js
  - MongoDB for data storage (with Mongoose for database interaction)
- **Other Tools:**
  - Postman for API testing
  - Git for version control
  - GitHub for code repository hosting

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/Darshan0244/RecipeWebsite.git
```

### 2. Navigate to the project directory:

```bash
cd RecipeWebsite
```

### 3. Install dependencies for both the client and the server:

#### For the Client:

```bash
cd Client
npm install
```

#### For the Server (API):

```bash
cd ../API
npm install
```

### 4. Create a `.env` file in the API directory with the following details:

```env
MONGO_URI=<Your MongoDB connection string>
JWT_SECRET=<Your JWT secret>
```

### 5. Start the server and the client:

#### Server (API):

```bash
cd API
npm start
```

#### Client (Frontend):

```bash
cd Client
npm start
```

### 6. Open the website in your browser by navigating to `http://localhost:3000`.

## API Endpoints

- **GET** `/recipes` - Get all recipes
- **POST** `/recipes` - Add a new recipe
- **PUT** `/recipes/:id` - Update a recipe
- **DELETE** `/recipes/:id` - Delete a recipe

## Screenshots

(Include screenshots of your website here, if applicable)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

