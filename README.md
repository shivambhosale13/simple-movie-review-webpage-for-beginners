Movie Review App
About
The Movie Review App is a simple web application that allows users to view, submit, and manage movie reviews.
It is built using the MEAN stack (MongoDB, Express, AngularJS, Node.js) with a focus on simplicity and ease of use.

Features
View a list of movies and their reviews

Add new movies with ratings and comments

Simple, clean frontend built with AngularJS

Backend API built with Node.js and Express

MongoDB used for storing movie data

Technologies Used
Frontend: HTML, CSS, AngularJS

Backend: Node.js, Express

Database: MongoDB

Project Structure
csharp
Copy
Edit
movie-review-app/
│── server.js               # Backend API (Node.js + Express)
│── models/
│   ├── Movie.js            # MongoDB Schema
│── public/                 # Frontend (AngularJS + UI)
│   ├── index.html          # Main HTML file
│   ├── css/
│   │   ├── style.css
│   │   ├── homestyle.css
│   ├── js/
│   │   ├── app.js
│   │   ├── controllers/
│   │   │   ├── movieController.js
│   │   ├── services/
│   │   │   ├── movieService.js
│   ├── images/             # Movie images 
│── package.json            # Project dependencies
How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone <your-repo-url>
Install backend dependencies:

bash
Copy
Edit
cd movie-review-app
npm install
Make sure MongoDB is running locally.

Start the server:

nginx
Copy
Edit
node server.js
Open your browser and go to:

arduino
Copy
Edit
http://localhost:3000
Notes
The app is kept intentionally simple for easier understanding and customization.

Designed for learning and small projects.

License
This project is open-source and free to use.
