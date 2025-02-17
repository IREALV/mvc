# MVC Project Template - using NodeJS, Express, Sequelize and MySQL
Created for educational purposes for the fifth-degree groups of Software Engineering, at UNIPOLI Dgo, for the Client-Server course.

## Getting Started

These instructions will guide you through cloning and installing the project on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (version 22.13.01 or higher)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Installation

1. **Clone the repository**

    Clone the project repository to your local machine using the following command:

    ```bash
    git clone https://github.com/jlbautista/mvc.git
    ```

2. **Navigate to the project directory**

    Change the directory to the project folder:

    ```bash
    cd mvc
    ```

3. **Install dependencies**

    Install the required dependencies using npm:

    ```bash
    npm install
    ```

### Running the Project

To run the project, use the following command:

```bash
npm start
```

The application should now be running on [http://localhost:3001](http://localhost:3001).

### Additional Scripts

Here are some additional npm scripts you might find useful:

- **Run tests:**

    ```bash
    npm test
    ```

- **Build the project:**

    ```bash
    npm run build
    ```

### Configuration

If there are any environment variables required for your project, make sure to set them up. You can create a `.env` file in the root of the project directory and add your variables there. For example:

```
PORT = 3001

DB_HOST = localhost
DB_USER = your_db_user
DB_PASS = your_db_user_password
DB_NAME = your_database
```

### Troubleshooting

If you encounter any issues during installation or running the project, refer to the [Issues](https://github.com/jlbautista/mvc_5a/issues) section on GitHub for solutions or to report a new issue.
