# React Movie App

A React + Tailwind CSS movie discovery app powered by the TMDB API, with Firebase Authentication (Email/Password + Google).

## Demo
![Movie App Demo](./movie.gif)

## Features
- Browse popular movies and search by title
- Movie detail page (poster, overview, rating)
- Firebase Auth: Email/Password and Google Sign-In

## Tech Stack
- React (Create React App)
- React Router
- Tailwind CSS
- Firebase Authentication
- TMDB API

## Project Structure (src/)
- `assets/icons/` icons and static assets
- `auth/` Firebase configuration
- `components/` reusable UI components
- `context/` global state (Auth and Movie context)
- `helpers/` toast notification helper
- `pages/` Main, MovieDetail, Login, Register
- `router/` route definitions
- `App.js` app shell
- `index.js` entry

## Run Locally

1. Clone and install:

   ```bash
   git clone https://github.com/yldzozgur/react-movieapp.git
   cd react-movieapp
   npm install
   ```

2. Create a `.env` file in the project root (next to `package.json`):

   ```env
   REACT_APP_TMDB_KEY=your_tmdb_api_key

   REACT_APP_apiKey=your_firebase_api_key
   REACT_APP_authDomain=your_firebase_auth_domain
   REACT_APP_projectId=your_firebase_project_id
   REACT_APP_storageBucket=your_firebase_storage_bucket
   REACT_APP_messagingSenderId=your_firebase_sender_id
   REACT_APP_appId=your_firebase_app_id
   ```

3. Start the dev server:

   ```bash
   npm start
   ```

   Open http://localhost:3000

## Scripts
- `npm start` runs the dev server
- `npm run build` creates a production build
- `npm test` runs tests

## Roadmap
- Pagination / infinite scroll
- Favorites / watchlist
- Loading skeletons and better error handling

## Author
Ozgur Yildiz
[GitHub](https://github.com/yldzozgur) | [LinkedIn](https://linkedin.com/in/yldzozgur)
