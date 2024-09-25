# PWA Text Editor

## Description

This is a Progressive Web Application (PWA) text editor that can be used to write and save code snippets or notes. It works both online and offline, thanks to its service worker and IndexedDB integration. The application allows you to install it as a desktop app, providing a native-like experience.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation

To install and run this project locally, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Navigate into the project directory:
   ```bash
   cd your-repo
   ```

3. Install the dependencies for both the server and the client:
   ```bash
   npm install
   ```

4. Build the client:
   ```bash
   cd client
   npm install
   npm run build
   ```

5. Start the server:
   ```bash
   cd ..
   npm start
   ```

The server will start on `http://localhost:3000`.

## Usage

Once the application is running, you can access it by visiting `http://localhost:3000` in your browser.

### Features:
- Write and save text or code snippets.
- Your content is saved automatically using IndexedDB and can be retrieved even if the browser is closed and reopened.
- The app can be installed as a PWA, allowing it to be run from your desktop like a native application.
- Works offline thanks to a service worker that caches files.
  
To install the application as a PWA:
- Open the app in Chrome or any PWA-capable browser.
- Click on the **Install** button or the browser's install prompt (usually found in the address bar).
  
## Features

- **Offline Support**: The application uses a service worker to cache essential assets, enabling offline functionality.
- **IndexedDB for Persistence**: Content entered in the text editor is saved to IndexedDB, allowing data to persist even when the application is closed.
- **PWA Installation**: The app can be installed as a PWA on both desktop and mobile devices for a native-like experience.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express**: Web server framework for Node.js.
- **Webpack**: Module bundler for JavaScript files.
- **Workbox**: Service worker library for handling caching.
- **IndexedDB**: Client-side database for saving content locally.
- **HTML/CSS/JavaScript**: Standard web technologies for front-end functionality.
- **Babel**: JavaScript compiler to ensure compatibility with older browsers.

## License

This project is licensed under the MIT License.
