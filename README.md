# Just Another Text Editor (JATE)

## Description

Just Another Text Editor (JATE) is a Progressive Web Application (PWA) that allows users to create notes or code snippets with or without an internet connection. It features data persistence techniques using IndexedDB and can function offline. This project demonstrates modern web development techniques, including the use of Webpack, service workers, and caching.

## Table of Contents

- Installation
- Usage
- Features
- Technologies
- Acknowledgements
- License
- Contract

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/BrendaHaight/text-editor.git
cd text-editor
```

2. Install server dependencies:

```bash
npm install
```

3. Navigate to the client directory and install dependencies:

```bash
cd client
npm install
```

4. Build the client

```bash
npm run build
```

5. Navigate back to the project root and start the server:

```bash
cd ..
npm run start
```

## Usage

To run the application in development mode, use the following command:

```bash
npm run start:dev
```

This command will concurrently start the server and client in development mode.

Open a web browser and navigate to http://localhost:3000 to access the application.

## Features

- Offline Functionality: The application works offline by leveraging service workers and caching.

- IndexedDB Integration: Data persistence using IndexedDB ensures that notes and code snippets are saved and retrievable.

- PWA Installation: Users can install the application on their devices for a native app-like experience.

- Modern Web Development Techniques: Utilizes Webpack, Babel, and other modern development tools and practices.

## Technologies

**- Frontend:** - HTML - CSS - JavaScript - CodeMirror - Webpack - Babel - Service Workers - IndexedDB

**- Backend:** - Node.js - Express.js

## Acknowledgements

This project is part of my journey to become a software developer, and it was provided as a starting point in my coding bootcamp at the University of Texas at Austin. Special thanks to the bootcamp instructors and the support team for their guidance and assistance.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, feel free to contact me at:

**- Name: Brenda Haight**

_- Email: brendahaightt@gmail.com_
