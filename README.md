# Hotel BT Mock Website

A responsive, multi-page hotel landing website built with React. Showcases home, about, and contact pages with dynamic navigation, custom layouts, and styled components.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [License](#license)

## Demo

![Site Preview](public/images/showcase.jpg)

_Live demo coming soon._

## Features

- **Home Page**: Hero banner, service section, and quick info blocks.
- **About Page**: Hotel description, circular image layout, and guest reviews.
- **Contact Page**: (Coming soon) Form for inquiries and contact details.
- **Responsive Design**: Mobile-first CSS and flexible layouts.
- **Reusable Components**: `<NavBar>` and `<Footer>` across pages.

## Tech Stack

- React
- CSS Modules and global styles
- Create React App tooling

## Project Structure

```
├── public/             # Static assets and HTML template
│   ├── images/         # Example images used in pages
│   ├── favicon.ico
│   └── index.html
├── src/                # Application source code
│   ├── components/     # Shared UI components (NavBar, Footer)
│   ├── pages/          # Page-level components (Home, About, Contact)
│   ├── styles/         # CSS files scoped per page or component
│   ├── utils/images/   # Imported image assets
│   ├── App.js          # Root application with routing
│   ├── index.js        # Entry point
│   └── index.css       # Global styles
├── examples/           # Example markdown checks and guides
└── README.md           # Project documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Nimith-M-Gowda/Hotel-website-mock.git
   cd Hotel-website-mock
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

- Start the development server:
  ```bash
  npm start
  ```
  The app runs at [http://localhost:3000](http://localhost:3000).

- Run tests:
  ```bash
  npm test
  ```

- Build for production:
  ```bash
  npm run build
  ```

## Deployment

Build and deploy the `build/` folder to any static hosting service (Netlify, Vercel, GitHub Pages).

## License

MIT © Nimith-M-Gowda
