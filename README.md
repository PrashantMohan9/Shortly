# URL Shortener
Project URL [Live Demo](https://ishort-ly.herokuapp.com/)
This project was generated with version 10.0.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Features:
1. Users can hash the URL with/without the query string.
2. Users can login and can see all the hashed URL's by the user along with the click count of that hashed URL.

## Additional Features:
Used jwt (JSON Web Token) for protecting the API routes.
All the passwords are hashed before storing into the database using bycrypt.
Same Email cannot be used for creating multiple users.
Implemented Auth Guard at the frontend for protecting unauthorized access to the routes.

## Steps to Run the Application:
Open Terminal in the root directory of the project and type: ng serve --o
Open another terminal in the root directory of the project and type: node server.js
