# Xora - SaaS Landing Page

This is a modern and visually appealing landing page for a SaaS product named "Xora". It's built with React and Vite, and styled with Tailwind CSS.

![Xora Screenshot](./public/images/screen.jpg)

## Features

- **Hero Section:** A captivating introduction to the product.
- **Features:** Detailed section showcasing the product's capabilities.
- **Pricing:** Clear and concise pricing plans.
- **FAQ:** Answering common questions to help potential customers.
- **Testimonials:** Building trust with quotes from happy customers.
- **Download Section:** A call-to-action to get started with the product.
- **Responsive Design:** Fully responsive layout that looks great on all devices.

## Tech Stack

- **Frontend:** [React](https://reactjs.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Linting:** [ESLint](https://eslint.org/)
- **Animations:** CSS transitions

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need to have Node.js and npm installed on your machine.

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username/xora.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

### Running the Application

To run the application in development mode, use the following command:

```sh
npm run dev
```

This will start the development server at `http://localhost:5173`.

### Building for Production

To create a production build, run:

```sh
npm run build
```

This will create a `dist` folder with the optimized and minified files for production.

## Folder Structure

```
xora/
├── public/               # Static assets
├── src/
│   ├── assets/           # React and other assets
│   ├── components/       # Reusable React components
│   ├── constants/        # Constants for the application
│   ├── sections/         # Different sections of the landing page
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # Entry point of the application
│   └── index.css         # Global styles
├── .eslintrc.cjs         # ESLint configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── vite.config.js        # Vite configuration
└── package.json          # Project metadata and dependencies
```
