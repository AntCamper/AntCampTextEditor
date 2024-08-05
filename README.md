# J.A.T.E (Just Another Text Editor)

## Description
J.A.T.E is a Progressive Web Application (PWA) text editor that runs in the browser. It features data persistence techniques that serve as redundancy in case the browser does not support one of the options. 

## Features
- Create notes or code snippets with or without an internet connection
- Reliably retrieve them for later use
- Automatic saving of content when the DOM window is unfocused
- Works offline
- Can be installed as a desktop application

## Installation
1. Clone the repository to your local machine.
2. Navigate to the root directory in your terminal.
3. Run `npm install` to install all dependencies.
4. Run `npm run start:dev` to start the development server.

## Usage
1. Open the application in your browser.
2. Start typing your notes or code snippets.
3. Your content will be automatically saved when you click off the DOM window.
4. To install the application on your desktop, click the "Install" button in the application.

## Technologies Used
- JavaScript
- IndexedDB for local storage
- Webpack for bundling
- Express.js for the server

## Deployment
This application is deployed on Render. You can visit the live site at : https://antcamptexteditor.onrender.com
