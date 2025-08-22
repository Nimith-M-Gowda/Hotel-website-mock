# Hotel Website Mock

A static, responsive hotel landing site built with React. This project demonstrates core React concepts, component-driven architecture, CSS styling, and asset organization to create a simple hotel website mockup.

## Features

- **Home Page**: Full-screen header with background image, call-to-action button, and service highlights.
- **About Page**: Hotel overview, guest reviews carousel, and image assets.
- **Contact Page**: Contact form and details (coming soon).
- **Reusable Components**: Navigation bar (`NavBar.js`) and footer (`Footer.js`) shared across pages.
- **Asset Management**: Images organized under `src/utils/images` and `public/images`.
- **Styling**: Each page and component has its own CSS module for scoped styles.

## Demo

![Screenshot of Home Page](public/images/showcase.jpg)

## Getting Started

### Prerequisites

- Node.js (>=14.x)
- npm (>=6.x)

### Installation

```bash
# Clone the repository
git clone https://github.com/Nimith-M-Gowda/Hotel-website-mock.git
cd Hotel-website-mock

# Install dependencies
npm install
```

### Available Scripts

In the project directory, you can run:

- `npm start`
  Starts the development server at [http://localhost:3000](http://localhost:3000).
- `npm run build`
  Bundles the app into static files for production in the `build` folder.
- `npm test`
  Launches the test runner (configured via Create React App).

## Project Structure

```
Hotel-website-mock/
├── public/              # Public assets (served statically)
│   ├── images/          # Site images
│   └── index.html       # HTML template
├── src/                 # React application source
│   ├── components/      # Shared UI components (NavBar, Footer)
│   ├── pages/           # Page views (Home, About, Contact)
│   ├── styles/          # CSS modules for each page/component
│   ├── utils/images/    # Imported image assets
│   ├── App.js           # Root React component
│   ├── index.js         # Application entry point
│   └── index.css        # Global styles
├── package.json         # Project metadata & scripts
└── README.md            # Project documentation
```

## Customization

- Replace image assets in `src/utils/images` or `public/images`.
- Tweak styles in `src/styles/*.css` per page/component.
- Extend components in `src/components` with new sections or features.

## Learn More

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). For more information on CRA, React, and best practices, check out:

- React documentation: https://reactjs.org/
- Create React App docs: https://facebook.github.io/create-react-app/docs/getting-started

<!-- @DeepDocs Generated on PROJECT STARTUP -->