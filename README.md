# Movie App

A React project scaffold for a movie app, bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Status

This repository currently contains only the initial project setup. The single component (`src/components/App.js`) renders the placeholder text "Project Setup". No movie-related features have been built yet.

## Tech Stack

- React 18 (`react`, `react-dom`)
- Create React App (`react-scripts` 5.0.1)
- React Testing Library and jest-dom (installed as dependencies; no tests are included yet)

## Project Structure

```
movie-app/
├── public/              # Static files and the HTML template (index.html, icons, manifest.json)
├── src/
│   ├── components/
│   │   └── App.js       # Root component (placeholder)
│   ├── index.js         # Entry point; renders <App /> into #root
│   └── index.css        # Global styles
└── package.json
```

## Prerequisites

- [Node.js](https://nodejs.org/) and npm

## Getting Started

```bash
git clone https://github.com/iSouvikKhan/movie-app.git
cd movie-app
npm install
npm start
```

The development server runs at [http://localhost:3000](http://localhost:3000). The page reloads when you make changes.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode at [http://localhost:3000](http://localhost:3000).

### `npm test`

Launches the test runner in interactive watch mode. See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production into the `build` folder. The build is minified and the filenames include hashes. See [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

Copies all build configuration (webpack, Babel, ESLint, etc.) into the project so you have full control over it. You don't have to ever use `eject`.

## Learn More

- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React documentation](https://reactjs.org/)
