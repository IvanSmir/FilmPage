# FilmPage - Movie Information Website

FilmPage is a dynamic website that allows users to explore and interact with movie information. It features a responsive design and integrates with a movie database API to provide up-to-date content.

## Key Features

- **Movie Slider**: Showcases trending movies with an interactive slider on the homepage.
- **Popular Movies**: Displays a grid of popular movies.
- **Search Functionality**: Allows users to search for specific movies.
- **Movie Details**: Provides detailed information about individual movies, including plot, ratings, and cast.
- **Favorites**: Users can add movies to their favorites list.
- **Comments**: Users can leave comments and ratings on movie pages.

## Project Structure

The project is organized into several HTML pages and supporting JavaScript and CSS files:

- `index.html`: Homepage with movie slider and popular movies
- `movie.html`: Individual movie details page
- `favorites.html`: User's favorite movies list
- `results.html`: Search results page

Supporting files:
- `css/styles.css`: Main stylesheet
- `js/script.js`: Main JavaScript file for homepage functionality
- `js/moviescript.js`: Handles movie detail page functionality
- `js/search.js`: Manages search functionality
- `js/favorites.js`: Manages favorites functionality
- `js/comentarios.js`: Handles comment system

## Technology Stack

- HTML5
- CSS3 (with custom styles and animations)
- JavaScript (ES6+)
- Font Awesome for icons
- The Movie Database (TMDb) API for movie data

## Setup and Usage

1. Clone the repository
2. Open `index.html` in a web browser to view the site
3. Ensure you have an active internet connection for API calls and font loading

## API Integration

The site uses TMDb API for fetching movie data. An API key is required and should be kept secure. The current implementation includes the API key in the JavaScript files, which is not recommended for production use.

## Responsive Design

The site is designed to be responsive, with a mobile-first approach. It uses media queries to adjust layouts for different screen sizes.

## Future Improvements

- Implement user authentication for personalized favorites and comments
- Enhance error handling and loading states
- Optimize API calls and implement caching
- Improve accessibility features

## Contributing

Contributions to improve FilmPage are welcome. Please follow standard GitHub pull request procedures to submit your changes.
