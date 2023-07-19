
# Sequelize CRUD App

This is a simple CRUD (Create, Read, Update, Delete) app using Node.js, Express, Sequelize, and MySQL to manage "users" in a database.

## Getting Started

### Prerequisites

- Node.js and npm installed on your system
- MySQL database set up with credentials (replace 'your_database_name', 'your_username', and 'your_password' in config/database.js)

### Installing

1. Clone this repository
git clone https://github.com/your-username/sequelize-crud-app.git

2. Install dependencies
cd 
npm install

### Running the App

Start the server by npm start


The server will be running at `http://localhost:3000`.

## API Endpoints

### Create a User

- **Endpoint:** `router.post('/', userController.createUser);`
  
### Get All Users

- **Endpoint:** ` router.get('/', userController.getAllUsers);`

### Get Users by ID

- **Endpoint:** ` router.get('/:id', userController.getUserById);`

### Update a User

- **Endpoint:** `router.put('/:id', userController.updateUser)`

### Delete a User

- **Endpoint:** `router.delete('/:id', userController.deleteUser);`




