# Hotel Website Mock

A simple, responsive hotel website mockup built with React. This project demonstrates a basic multi-page layout featuring a Home page, About page, and a functional Contact form, along with a reusable navigation bar and footer components.

## Features

- **Home Page** – Showcase images and a brief welcome message.
- **About Page** – Detail information about the hotel and its services.
- **Contact Page** – Interactive contact form (name, email, message) that logs submissions and resets the form. Includes hotel location, phone number, and email contact banners.
- **Reusable Components** – `NavBar` and `Footer` components shared across all pages.
- **Responsive Design** – Mobile-first CSS styles ensuring compatibility across devices.
- **Asset Management** – Local images and icons loaded via React and CSS.

## Tech Stack

- React
- JavaScript (ES6+)
- CSS Modules
- [react-icons](https://react-icons.github.io/react-icons/) for iconography

## Project Structure

```bash
├── public/              # Static files (HTML, favicon, manifest)
├── src/                 # React application source code
│   ├── components/      # Shared UI components (NavBar, Footer)
│   ├── pages/           # Page-level components (Home, About, Contact)
│   ├── styles/          # CSS style sheets
│   ├── utils/           # Utility assets (images)
│   ├── App.js           # Root application component
│   └── index.js         # Entry point
├── examples/            # Example usage or external examples
├── package.json         # Project metadata and dependencies
└── README.md            # Project documentation
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nimith-M-Gowda/Hotel-website-mock.git
   cd Hotel-website-mock
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Run the development server**
   ```bash
   npm start
   ```
   The app will open at `http://localhost:3000`.
4. **Build for production**
   ```bash
   npm run build
   ```

## Contact Form Behavior

- On submission, form values (Name, Email, Message) are logged to the console.
- A mock fetch request is sent to `https://jsonplaceholder.typicode.com/todos/1`.
- After submission, the form fields reset to empty.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is open source and available under the [MIT License](LICENSE).