![Github license](https://img.shields.io/badge/license-MIT-blueviolet.svg)

# justAnotherTextEditor

A text editor that runs in the browser and is a single-page application that features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. This application will also function offline!

## Live Links

- 📽️ Deployed app:
- 🌍 Repository: https://github.com/mblackwellgca/justAnotherTextEditor

## Description

- AS A developer
  - I WANT to create notes or code snippets with or without an internet connection
  - SO THAT I can reliably retrieve them for later use

## Installation

The dev dependencies concurrently and nodemon are required. The dependencies express and if-env are also required.

## Criteria

GIVEN a text editor web application
* WHEN I open my application in my editor
    * THEN I should see a client server folder structure
* WHEN I run `npm run start` from the root directory
    * THEN I find that my application should start up the backend and serve the client
* WHEN I run the text editor application from my terminal
    * THEN I find that my JavaScript files have been bundled using webpack
* WHEN I run my webpack plugins
    * THEN I find that I have a generated HTML file, service worker, and a manifest file
* WHEN I use next-gen JavaScript in my application
    * THEN I find that the text editor still functions in the browser without errors
* WHEN I open the text editor
    * THEN I find that IndexedDB has immediately created a database storage
* WHEN I enter content and subsequently click off of the DOM window
    * THEN I find that the content in the text editor has been saved with IndexedDB
* WHEN I reopen the text editor after closing it
    * THEN I find that the content in the text editor has been retrieved from our IndexedDB
* WHEN I click on the Install button
    * THEN I download my web application as an icon on my desktop
* WHEN I load my web application
    * THEN I should have a registered service worker using workbox
* WHEN I register a service worker
    * THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
* WHEN I deploy to Heroku
    * THEN I should have proper build scripts for a webpack application

## Usage

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

## Credits:

- 🏫 Sandra Smith
- 💻 Christopher Ponzio https://github.com/ChristopherPonzio
- 🔗 https://www.w3schools.com/
- 🔗 https://stackoverflow.com/
- 🔗 https://chooselicense.com/
- 🔗 https://img.shields.io/


## License

## MIT License
