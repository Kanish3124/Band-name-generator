# Random Band Name Generator 🎸

A fun web application that generates unique band names by combining a random adjective and noun. Built with Node.js, Express.js, and EJS, this project demonstrates dynamic web development with a simple and interactive interface.

## Features 🚀
- Generates a random band name on each submission.
- Dynamic rendering of content using EJS templating.
- Lightweight and easy to use.

## Technologies Used 🛠️
- **Node.js**: Backend server framework.
- **Express.js**: Simplified routing and middleware handling.
- **EJS**: For dynamic templating of web pages.
- **HTML/CSS**: Front-end design and styling.
- **JavaScript**: Core logic for random name generation.

## How It Works ⚙️
1. The server uses Express.js to handle GET and POST requests.
2. On the home page (`/`), a form lets users submit a request to generate a band name.
3. A random adjective and noun are selected from predefined arrays to create a unique band name.
4. The generated name is dynamically rendered back to the user using EJS.

## Installation 🛠️
1. Clone the repository:
   ```bash
   git clone https://github.com/Kanish3124/Band-name-generator.git

2. Navigate to the project directory:
   ```bash
   cd Band-name-generator

3. Install dependencies:
   ```bash
   npm install

4. Start the server:
   ```bash
   node app.js

5. Open your browser and visit: http://localhost:3000

## File Structure 📂
```php

Band-name-generator/
├── public/            # Static assets (CSS, images, etc.)
├── views/             # EJS templates
│   └── index.ejs      # Main HTML file
├── app.js             # Main server file
├── package.json       # Project metadata and dependencies
└── README.md          # Project documentation
```
## License 📜
This project is licensed under the MIT License.

## Acknowledgments 🙌
Inspired by the fun of creating quirky and creative band names!
