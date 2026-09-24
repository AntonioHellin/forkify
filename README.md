# forkify

A modular vanilla JavaScript recipe management platform featuring real-time API queries, persistent bookmarking, dynamic serving adjustments, and custom recipe creation.

## Project Overview

`forkify` provides an interactive recipe interface engineered with ES6+ JavaScript following strict Model-View-Controller (MVC) architectural separation. Built with Parcel, it integrates with the Forkify v2 REST API to deliver instant recipe searches, fractional ingredient calculation, and local storage persistence.

## Features

- **Recipe Search & Pagination**: Search through over a million culinary recipes with paginated result views.
- **Dynamic Servings Scaling**: Instant recalculation of ingredient measurements when servings increase or decrease.
- **Bookmark Storage**: Save favorite recipes to browser local storage for offline reference.
- **Custom Recipe Creator**: Modal form allowing users to publish custom recipes with automated ingredient parsing.

## Prerequisites

- [Node.js](https://nodejs.org/) (version 16.x, 18.x, or later)
- [npm](https://www.npmjs.com/) (version 8.x or later)

## Installation/Build

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/AntonioHellin/forkify.git
   cd forkify
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   ```bash
   cp .env.example .env
   ```
   Add your Forkify API key to `.env` for custom recipe uploads.

4. Build for production:
   ```bash
   npm run build
   ```

## Usage

Start the local Parcel development server:
```bash
npm start
```
The application will open automatically in your browser at `http://localhost:1234`.

## License

This project is licensed under the ISC License.
