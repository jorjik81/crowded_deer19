# Progressive Web Applications (PWA) Challenge: Text Editor

## Description

This project is part of the Progressive Web Applications (PWA) Challenge for Week 19 of the course. The goal of this challenge is to build a text editor that runs in the browser and meets the criteria of a Progressive Web Application. The text editor will be a single-page application with data persistence techniques and offline functionality.

## Task

The task is to build a text editor using an existing application as a starting point. The application should implement methods for getting and storing data to an IndexedDB database. The `idb` package, a lightweight wrapper around the IndexedDB API, should be used for this purpose. The application should be deployed to Render using the Render Deployment Guide on The Full-Stack Blog.

## User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use


## Installation

To get started with the project, clone the starter code repository and create your own repository using the starter code. Do not fork the starter code repository. Before you start, make sure to clone the starter code.

## Usage

1. Open the application in your preferred editor.
2. Run `npm run start` from the root directory to start the backend and serve the client.
3. Run the text editor application from your terminal.
4. Verify that the JavaScript files have been bundled using webpack.
5. Check that the webpack plugins have generated the HTML file, service worker, and manifest file.
6. Use the text editor and ensure that it functions without errors.
7. Open the text editor and verify that IndexedDB has created a database storage.
8. Enter content in the text editor and click off the DOM window to save the content with IndexedDB.
9. Reopen the text editor after closing it and confirm that the content has been retrieved from IndexedDB.
10. Click on the Install button to download the web application as an icon on your desktop.
11. Load the web application and check that a service worker is registered using workbox.
12. Register the service worker and ensure that static assets are pre-cached upon loading, along with subsequent pages and static assets.
13. Deploy the application to Render and ensure that proper build scripts for a webpack application are in place.

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

The project was created Giorgi Jorjadze as part of the Progressive Web Applications (PWA) Challenge for Week 19 of the course.





