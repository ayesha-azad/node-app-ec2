# Node App

A simple Node.js web application with a static frontend.

## Project Structure

```
node-app/
├── server.js           # Express server entry point
├── package.json        # Project dependencies and metadata
├── README.md          # This file
└── public/            # Static assets
    ├── index.html     # Main HTML file
    └── style.css      # Stylesheet
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository
   ```bash
   git clone <repository-url>
   cd node-app
   ```

2. Install dependencies
   ```bash
   npm install
   ```

### Running the Server

Start the application:
```bash
npm start
```

The server will run on `http://localhost:3000` (or the port specified in your `.env` file).

## Features

- Simple HTTP server built with Express
- Static file serving for HTML and CSS
- Lightweight and easy to extend

## Usage

Once the server is running, open your browser and navigate to `http://localhost:3000` to access the application.

## Development

To make changes:
1. Edit `server.js` for backend logic
2. Modify `public/index.html` for page content
3. Update `public/style.css` for styling

## License

MIT
