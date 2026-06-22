# Media Search Application

A modern media search application built with React, Redux Toolkit, and external media APIs. Users can search and explore Photos, Videos, and GIFs from a single interface.

## Features

* Search photos, videos, and GIFs
* Real-time search functionality
* Redux Toolkit state management
* Responsive user interface
* Category-based media filtering
* Fast and interactive user experience
* Collection/Favorites page support

## Tech Stack

### Frontend

* React.js
* React Router DOM
* Redux Toolkit
* React Redux
* Tailwind CSS
* Axios

### APIs

* Pexels API
* GIF API Integration

## Project Structure

src/
├── api/
├── components/
│ ├── SearchBar.jsx
│ ├── Tabs.jsx
│ ├── ResultGrid.jsx
│ └── ResultCard.jsx
├── pages/
│ ├── HomePage.jsx
│ └── CollectionPage.jsx
├── redux/
│ ├── store.js
│ └── features/
│ └── searchSlice.js
├── App.jsx
└── main.jsx

## Installation

Clone the repository:

git clone https://github.com/your-username/media-search-app.git

Navigate to the project folder:

cd media-search-app

Install dependencies:

npm install

Start the development server:

npm run dev

## Environment Variables

Create a `.env` file in the root directory:

VITE_PEXELS_KEY=YOUR_API_KEY

## Usage

1. Enter a search term.
2. Select a media type (Photos, Videos, GIFs).
3. Browse the search results.
4. Open media items and manage collections.

## Future Improvements

* User authentication
* Download media functionality
* Infinite scrolling
* Dark/Light theme toggle
* Advanced search filters
* Favorites synchronization

## Author
Md Nazare Alam
MCA Student | Java Backend & Full Stack Enthusiast

## License
This project is developed for learning and portfolio purposes.
