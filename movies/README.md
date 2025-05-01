MOVIE APP
A React-based movie browser that lets users view popular movies, search for films, and manage a list of favorite movies using the TMDB API.

FEATURES
Browse popular movies using TMDB API

Search for movies by title

Add or remove favorites

Favorites are persisted using local storage

Responsive, interactive UI with dynamic movie cards

Navigation using React Router

TECH STACK
React (with Hooks & Context API)

React Router v6

CSS for styling

TMDB API for movie data

LocalStorage for persistence

src/
├── components/
│   ├── MovieCard.js
│   └── NavBar.js
├── contexts/
│   └── MovieContext.js
├── css/
│   ├── Home.css
│   ├── MovieCard.css
│   ├── Navbar.css
│   └── Favorites.css
├── pages/
│   ├── Home.js
│   └── Favorites.js
├── services/
│   └── api.js
├── App.js
└── index.js

