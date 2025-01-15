# Documentary Streaming Platform

## Overview

This project is a React-based web application that utilizes The Movie Database (TMDB) API to showcase a wide range of documentaries. The platform allows users to explore different genres of documentaries, view detailed information about each documentary, and stream them directly on the platform. The application is built with responsive design principles, using Tailwind CSS for styling and Redux Toolkit for efficient state management.

## Features

- **Dynamic Dashboard**: A central hub displaying documentaries in various categories, such as trending, top-rated, and genres.
- **Detailed View**: Clicking on a documentary card opens a detailed page with information like cast, genre, ratings, and a link to the documentary video.
- **Responsive Design**: The application is fully responsive, optimized for both desktop and mobile screens, and built using Tailwind CSS.
- **State Management**: Uses Redux Toolkit for managing global state, enabling smooth data flow and efficient component re-rendering.
- **Navigation**: Implements React Router for seamless and intuitive navigation across pages.
- **Video Streaming**: Leverages the TMDB API to stream documentary videos directly from the platform.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/documentary-streaming-platform


## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Madhav16062004/documentary-streaming-platform
   ```
2. Navigate to the project directory:
   ```
   cd documentary-streaming-platform
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Create a `.env` file based on the `.env.example` template and add your TMDB API key:
   ```
   VITE_TMDB_API_KEY=your_api_key_here
   ```
5. Start the development server:
   ```
   npm run dev
   ```

## Built With

- [React](https://reactjs.org/) - The web framework used
- [Tailwind CSS](https://tailwindcss.com/) - For styling
- [Redux Toolkit](https://redux-toolkit.js.org/) - State management
- [Axios](https://github.com/axios/axios) - HTTP client
- [React Router](https://reactrouter.com/) - For routing
- [Vite](https://vitejs.dev/) - Build tool

## Project Structure

- `.env.example` - Template for environment variables.
- `.eslintrc.cjs` - ESLint configuration.
- `package.json` - Project metadata and dependencies.
- `postcss.config.js` - PostCSS configuration.
- `src/components` - React components.
- `src/features` - Redux slices.
- `src/App.jsx` - Main application component.
- `src/index.css` - Global styles.
- `vite.config.js` - Configuration for Vite.
- `vercel.json` - Configuration for Vercel deployment.

## Challenges & Solutions

- **API Integration**: Managed asynchronous data fetching with Redux Toolkit's async thunks.
- **Responsive Design**: Utilized Tailwind CSS for responsive layouts and styling.
- **State Management Complexity**: Simplified with Redux Toolkit, organizing state into slices.

## Future Enhancements

- Implement user authentication for personalized experiences.
- Add a search feature to find specific movies or TV shows.
- Optimize performance further, including lazy loading components.

## Deployment

Deployed on Vercel with automatic rewrites configuration for SPA routing support. See `vercel.json` for deployment settings.

## Contributing

Contributions are welcome!
