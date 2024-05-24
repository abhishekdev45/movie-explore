# Movie Explorer

[Deployd Link](https://movie-explore-eight.vercel.app/)

## Project Overview

Movie Explorer is a web application designed to provide users with a seamless experience in discovering movies. Utilizing the TMDB (The Movie Database) API, the app features a search function, and dedicated pages for top-rated, upcoming, and popular movies. Additionally, the application offers both dark and light themes for user preference.

## Development Process

1. **Project Initialization**:
   - Set up the project using `create-react-app` to scaffold the initial structure.
   - Integrated Tailwind CSS for rapid and customizable styling.

2. **API Integration**:
   - Registered and obtained an API key from TMDB.
   - Created services to interact with TMDB API endpoints for fetching data regarding movies.
   - Handled API requests and responses using axios for better promise-based HTTP requests.

3. **Feature Implementation**:
   - **Search by Keywords**: Developed a search bar that allows users to input keywords and receive relevant movie results.
   - **Top Rated Movies**: Created a dedicated page that displays movies sorted by their rating.
   - **Upcoming Movies**: Implemented a page showcasing movies that are scheduled to be released soon.
   - **Popular Movies**: Added a page that lists currently popular movies.
   - **Theme Toggle**: Integrated a theme toggle allowing users to switch between dark and light modes.

4. **UI/UX Enhancements**:
   - Used Tailwind CSS to style the application, ensuring a responsive and modern design.
   - Employed React state and context for managing theme state across the application.

5. **Testing and Deployment**:
   - Tested the application for functionality and responsiveness across different devices and browsers.
   - Deployed the application using a chosen hosting service, providing a live link for user access.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **TMDB API**: External API for fetching movie data.
- **Axios**: Promise-based HTTP client for API requests.


## Features

- **Search Movies by Keywords**: Allows users to find movies by entering keywords.
- **Top Rated Movies**: Displays a list of movies with the highest ratings.
- **Upcoming Movies**: Shows movies that are yet to be released.
- **Popular Movies**: Lists movies that are currently popular.
- **Dark and Light Themes**: Provides a toggle for users to switch between dark and light modes.

Thank you for checking out Movie Explorer. Enjoy exploring the world of movies!
