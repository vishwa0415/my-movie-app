# 🎬 Movie App

A movie discovery web application built with **React.js and Vite** as a learning project. The application uses the **TMDB API** to retrieve movie data and **Appwrite** for database functionality.

Users can search for movies, and the application tracks movie searches to display the most searched movies in the **Trending Movies** section.

## 🚀 Features

- 🔎 Search for movies
- 🎬 Browse movie information
- 🔥 Display trending movies based on search frequency
- 📊 Track movie searches
- 🗄️ Store search data using Appwrite
- 🎨 Responsive UI with Tailwind CSS
- ⚡ Fast development with Vite
- ⚛️ Built with React.js

## 🛠️ Technologies Used

- **React.js** - Frontend library
- **Vite** - Development and build tool
- **Tailwind CSS** - Styling
- **TMDB API** - Movie data
- **Appwrite** - Database and backend services
- **JavaScript** - Application logic

## 🔥 Trending Movies

The application generates the trending movie section based on the number of times movies are searched.

The process works as follows:

1. A user searches for a movie.
2. The application sends the search request to the TMDB API.
3. Movie results are displayed.
4. The search information is stored in Appwrite.
5. Search counts are used to determine the most searched movies.
6. The most frequently searched movies are displayed in the Trending section.

