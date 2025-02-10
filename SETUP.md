# Project Setup Guide

Welcome to the Etsy API Store Automation Node App! Follow the steps below to set up the global variables and get the project running.

## Step 1: Clone the Repository

Clone the repository to your local machine using the following command:

```sh
git clone https://github.com/your-username/etsy-api-store-automation-node-app.git
cd etsy-api-store-automation-node-app
```

## Step 2: Install Dependencies

Install the required dependencies using npm:

```sh
npm install
```

## Step 3: Set Up Environment Variables

Create a `.env` file in the root directory of the project and add the following environment variables:

```properties
# Environment configuration for Etsy API Store Automation Node App

# Etsy API credentials
ETSY_API_KEY=your_etsy_api_key
ETSY_API_SECRET=your_etsy_api_secret
ETSY_ACCESS_TOKEN=your_etsy_access_token
ETSY_ACCESS_TOKEN_SECRET=your_etsy_access_token_secret

# Server configuration
PORT=3000

# Database configuration
DB_HOST=localhost
DB_PORT=5432
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_NAME=your_db_name

# Other configurations
LOG_LEVEL=info
```

Replace the placeholder values with your actual credentials and configuration details.

## Step 4: Start the Server

Start the server using the following command:

```sh
npm start
```

The server should now be running at `http://localhost:3000`.

## Step 5: Access the Application

Open your browser and navigate to `http://localhost:3000` to start using the Etsy API Store Automation Node App.

## Troubleshooting

If you encounter any issues, please refer to the project documentation or open an issue on the GitHub repository.

Happy coding!
