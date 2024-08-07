# TypeScript-Node-Express-TemplateEngine

This project is a backend application built with TypeScript, Node.js, Express.js, PostgreSQL, and Pug for template rendering. It includes various middlewares for security, logging, and compression, as well as rate limiting. The project also uses TailwindCSS for styling.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/lamiaaselim/SSR-ExpressJS.git
   ```
2. Navigate to the project directory:
   ```sh
   cd SSR-ExpressJS
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Usage

1. Start the development server:
   ```sh
   npm run dev
   ```
2. Open your browser and go to `http://localhost:8080` to see the application in action.

## Features

- **TypeScript**: TypeScript for type safety and modern JavaScript features.
- **ExpressJS**: Utilizes the lightweight and flexible Express framework.
- **API Integration**: Fetches data from external APIs and renders it on the server.
- **Templating Engine**: Uses Pug templating engine to render views.
- **TailwindCSS**: TailwindCSS for styling.
- **MVC Architecture**:

  ```sh
  SSR-ExpressJS/
  ├── controllers/ # Controllers for handling requests
  ├── middlewares/ # Custom middleware
  ├── models/ # Database models
  ├── public/ # Static files (CSS, JS, images)
  ├── routes/ # Express routes
  ├── services/ # Services for business logic
  ├── utils/ # Utility functions
  ├── views/ # Templating engine files (e.g., Pug)
  ├── .gitignore # Git ignore file
  ├── app.js # Main application file
  ├── package.json # NPM dependencies and scripts
  └── README.md # Project documentation

  ```

- **PostgreSQL**: PostgreSQL for the database.
- **Security and Performance Includes**:
  - Helmet for security headers.
  - Morgan for HTTP request logging.
  - Compression for response compression.
  - Express-rate-limit for rate limiting.
  - Error handling and 404 middlewares.
