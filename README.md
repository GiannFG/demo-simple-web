# Simple Express.js Website

A simple website built with Express.js that includes a home page and an about page.

## Installation

1. Clone this repository
2. Install dependencies:
```bash
npm install
```

## Running the Website

To run the website in development mode (with auto-reload):
```bash
npm run dev
```

To run the website in production mode:
```bash
npm start
```

The website will be available at http://localhost:3000

## Running with Docker

To build the Docker image:
```bash
docker build -t demo-simple-web .
```

To run the container:
```bash
docker run -p 3000:3000 demo-simple-web
```

The website will be available at http://localhost:3000 