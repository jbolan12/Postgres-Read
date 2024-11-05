# Postgres-Read

Quiz App

Description:
This Quiz App is built using Express.js and connects to a PostgreSQL database. It displays questions from the database and checks user answers, tracking the total score for correct answers.

-Features:

Displays a quiz question retrieved from a PostgreSQL database.
Checks the user's answer and provides feedback.
Tracks and displays the user's total score.
Technologies Used
Node.js: JavaScript runtime for building scalable applications.
Express.js: Web framework for Node.js to handle HTTP requests.
PostgreSQL: Database to store quiz questions.
Body-Parser: Middleware to parse incoming request bodies.

-Prerequisites:
PostgreSQL installed and running.
Database with a table named flags containing quiz questions (replace with actual table columns if necessary).

Installation
Clone the repository:

bash
git clone https://github.com/jbolan12/Postgres-Read

-Navigate into the project directory:

bash
cd <project-directory>
Install the dependencies:

bash
npm install
Configure the database:

Ensure PostgreSQL is running.
Adjust the database connection details in the code if necessary (username, password, host, port, etc.).

-Start the server:

bash
npm start
The app will be running at http://localhost:3000.

-Usage:
Go to http://localhost:3000 to start the quiz.

Answer the displayed question and submit.

The app will provide feedback on whether the answer was correct and keep track of the total score.

API Endpoints:
GET /
Retrieves a random quiz question from the database and displays it on the home page.
POST /submit
Accepts the user's answer, checks correctness, and returns feedback along with the next question.

License
This project is licensed under the MIT License.
