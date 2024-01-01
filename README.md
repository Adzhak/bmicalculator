# BMI Calculator

This is a simple Node.js application for calculating Body Mass Index (BMI). It allows users to input their height, weight, age, and gender to calculate and interpret their BMI.

## Installation

To run this application, you will need Node.js and npm (Node Package Manager) installed on your computer.

### Steps:

1. Clone the repository to your local machine using:
git clone [repository-url]

3. Navigate into the application's directory:
cd [local-repository-folder]

5. Install the dependencies using npm:
npm install

## Running the Application

Once the dependencies are installed, you can start the server with the following command:

npm start

The server runs on port 3000. To view the application, go to `http://localhost:3000` in your web browser.

## Dependencies

This application uses the following npm packages:

- `express`: A web application framework for Node.js, designed for building web applications and APIs.
- `nodemon` (optional): A utility that will monitor for any changes in your source and automatically restart your server. To use `nodemon`, install it globally with `npm install -g nodemon`, then start the app with `nodemon` instead of `npm start`.

## NPM Scripts

- `start`: Runs the app with node using the command `node app.js`.
- `dev`: (If you have installed `nodemon`) Runs the app in the development mode with `nodemon app.js`.

Make sure to replace `[repository-url]` and `[local-repository-folder]` with your actual repository URL and folder name.

## Application Structure

- `app.js`: The entry point for the server.
- `routes/bmiRoutes.js`: Routing logic for the BMI calculation.
- `views/index.html`: The HTML template for the application.
- `public/css`: Folder containing CSS files for styling.
- `public/js`: Folder containing JavaScript files for client-side logic.


