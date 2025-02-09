FPMarkets Exercise

This is the repository for the FPMarkets exercise project. Follow the steps below to set up and run the project for the first time.
Prerequisites

Before running the project, make sure you have the following installed:

    Node.js (including npm) — Download Node.js
    Git — Download Git

Steps to Run the Project
1. Clone the Repository

First, clone the repository to your local machine. Open your terminal (or Git Bash) and run:

git clone https://github.com/your-username/fpmarkets-exercise.git

Replace your-username with your actual GitHub username if necessary.
2. Navigate to the Project Directory

Move into the project directory:

cd fpmarkets-exercise

3. Install Dependencies

Install the required dependencies using npm. This will install all the necessary packages specified in package.json:

npm install

4. Run the Project

To start the project for the first time, you can run the following command:

npm start

This will start a local development server. You should see output similar to this:

> fpmarkets-exercise@1.0.0 start
> webpack-dev-server --mode development --open

The project will automatically open in your default browser. If it doesn't, you can navigate to the following URL:

http://localhost:3000

5. Additional Commands

    Build the Project: If you want to build the project for production, run:

npm run build

Run Tests: If you have tests set up for the project, you can run them with:

    npm test

6. Updating Dependencies

To update the dependencies in the future, you can run:

npm update

7. Troubleshooting

    If the project doesn't start, ensure you have the correct version of Node.js installed. You can check your Node.js version with:

node -v

If you see errors during npm install, make sure you have a stable internet connection and that the package.json file is not corrupted.
