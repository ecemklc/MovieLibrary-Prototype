# Movie Library with Prototype

![classMovie](https://github.com/user-attachments/assets/6c2f162a-92a1-4659-92d2-a06a256225f4)


This is a simple movie library application built using HTML, Bootstrap, and JavaScript. The application allows users to add, edit, and delete movies from a list. This project utilizes JavaScript prototypes for defining the structure and behavior of the movie library.

## Features

- **Add Movies**: Add new movies to the library by filling out the form.
- **Edit Movies**: Edit the details of existing movies.
- **Delete Movies**: Remove movies from the library.
- **Filter Movies**: Filter movies by genre (All, Comedy, Action, Science Fiction).

## Technologies Used

- HTML
- CSS
- Bootstrap
- JavaScript (with prototype-based object-oriented programming)

## Project Structure

- **index.html**: The main HTML file that contains the structure of the web page.
- **app.js**: Initializes the application and handles events.
- **movie.js**: Defines the `Movie` constructor function using prototypes.
- **movieList.js**: Defines the `MovieList` constructor function and its prototype methods for managing the movie list.
- **ui.js**: Defines the `UI` constructor function and its prototype methods for interacting with the user interface.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository**
2. **Open the project**:
    Open the `index.html` file in your preferred web browser.

## Code Explanation

### Movie Constructor
The `Movie` constructor function is defined in `movie.js`

### MovieList Constructor
The MovieList constructor function and its prototype methods are defined in `movieList.js`

### UI Constructor
The UI constructor function and its prototype methods are defined in `ui.js`

### Local Storage
The movie list is persisted using local storage. When the page loads, the movie list is fetched from local storage (if available)
