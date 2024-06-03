# Personal Bookshelf React App

## Overview
This is a React application called "Personal Bookshelf" that allows users to search for books using the Open Library API and maintain a personal bookshelf in the browser using localStorage.

### Features
- **Book Search Page**: Users can search for books by typing in a book's name. Search results are displayed in real-time as the user types. The Open Library API is used for fetching results. Pagination is not implemented; only the first 10 results of the first page are displayed.
- **Personal Bookshelf Page**: Users can add books from the search results to their personal bookshelf. The bookshelf is stored persistently using the Web Storage API (localStorage). A separate page is created to display the user's personal bookshelf.
- **Styling**: The application is styled using CSS. The pages are designed to be responsive and visually appealing.

### Tech Stack
- React
- React Router DOM
- Web Storage API (localStorage)
- CSS

## Usage
1. Clone the repository: `git clone https://github.com/Tarunchowdam/personal-bookshelf`
2. Install dependencies: `npm install`
3. Start the development server: `npm start`
4. Open your browser and navigate to `http://localhost:3000` to view the app.

## Live Demo
Check out the live demo [here](https://searchbooksbytarun.netlify.app/).

## Credits
- This project was created by [CHOWDAM TARUNKUMAR].

## License
This project is licensed under the [MIT License](LICENSE).
