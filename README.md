🎬 # Movie Management System

A Full-Stack Web Application using React, Node.js, Express, and SQLite

📖 Overview

The Movie Management System is a full-stack web application built to manage, search, and explore movie information.
It includes movie CRUD operations, director management, search with autocomplete, and poster-based movie display.

This project uses:

React.js – Frontend UI

Node.js + Express.js – Backend API

SQLite – Database

REST APIs – Communication between client & server

It functions like a mini-IMDB where users can add, update, search, and browse movies easily.

🚀 Features
🎞️ Movie Module

View all movies

Add new movies

Update existing movies

Delete movies

Display movie posters

Show movie IDs

Autocomplete movie search

🎬 Director Module

Add new directors

View all directors

Search director by name

View movies by specific directors

Display poster & movie details

🔍 Smart Search

Real-time search

Autocomplete suggestions

Instant filtering

Search via URL params /movies/search/:name

🧩 Extra Features

Navigation bar for easy routing

Modern UI with card layouts

Clean folder structure

Extensible for future features

🏗️ Tech Stack
Frontend

React.js

HTML5

CSS3

JavaScript

React Router DOM

Backend

Node.js

Express.js

Database

SQLite3

SQL schema & seed data

📂 Project Structure
movie-management-system/
│
├── backend/
│   ├── app.js
│   ├── moviesData.db
│   ├── movies.sql
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── Movies.js
│   │   │   ├── AddMovie.js
│   │   │   ├── UpdateMovie.js
│   │   │   ├── DeleteMovie.js
│   │   │   ├── Directors.js
│   │   │   ├── DirectorMovies.js
│   │   │   ├── SearchMovies.js
│   │   │   └── AddDirector.js
│   │   ├── components/
│   │   │   ├── Navbar.js
│   │   │   └── Navbar.css
│   │   ├── App.js
│   │   ├── App.css
│   │   └── index.js
│   └── package.json
│
└── README.md


🛠️ Backend Setup
cd backend
npm install

Run SQLite schema
sqlite3 moviesData.db ".read movies.sql"

Start backend server
node app.js


Backend runs at:

http://localhost:3000/

💻 Frontend Setup

In another terminal:

cd frontend
npm install
npm start


Frontend runs at:

http://localhost:3001/



🔗 API Endpoints
🎬 Movies API
Method	Endpoint	Description
GET	/movies/	Get all movies
GET	/movies/:movieId/	Get movie by ID
POST	/movies/	Add a movie
PUT	/movies/:movieId/	Update a movie
DELETE	/movies/:movieId/	Delete a movie
GET	/movies/search/:name	Search movies
🎬 Directors API
Method	Endpoint	Description
GET	/directors/	List all directors
POST	/directors/	Add a director
GET	/directors/search/:name	Search director
GET	/directors/:id/movies/	Movies by a director
🎯 Target Audience

This application is designed for:

Movie lovers

Film library users

Cinema staff

OTT viewers

Reviewers & bloggers

Students learning web development

Users can browse, search, and view movies easily with posters and clean UI.

🧪 Future Enhancements

User authentication (login/signup)

Movie categories & genres

Ratings and reviews

Pagination & filtering

Admin dashboard

Dark/Light theme

Upload poster instead of URL

🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first.

📜 License

This project is open-source and free to use.

💬 Author

Sainadh A
Full-Stack Developer
React | Node.js | SQLite
