# Progressive Web Applications (PWA): Text Editor

Week 19: Progressive Web Applications (PWA) Challenge

## Summary

A text editor application has been built that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

In order to build this text editor, an existing application was used and implemented methods for getting and storing data to an IndexedDB database. A package called `idb` was used, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

This full-stack application has been deployed to Heroku.


## Deployed Links

[Link to deployed Heroku]
[Link to Github] 

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN the user opens the application in the editor
THEN the user should see a client server folder structure
WHEN the user runs `npm run start` from the root directory
THEN the user finds that the application should start up the backend and serve the client
WHEN the user runs the text editor application from the terminal
THEN the user finds that the JavaScript files have been bundled using webpack
WHEN the user runs the webpack plugins
THEN the user finds that have a generated HTML file, service worker, and a manifest file
WHEN the user uses next-gen JavaScript in the application
THEN the user finds that the text editor still functions in the browser without errors
WHEN the user opens the text editor
THEN the user finds that IndexedDB has immediately created a database storage
WHEN the user enters content and subsequently click off of the DOM window
THEN the user finds that the content in the text editor has been saved with IndexedDB
WHEN the user reopens the text editor after closing it
THEN the user finds that the content in the text editor has been retrieved from the IndexedDB
WHEN the user clicks on the Install button
THEN the user downloads my web application as an icon on my desktop
WHEN the user loads the web application
THEN the user should have a registered service worker using workbox
WHEN the user registers a service worker
THEN the user should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN the user deploys to Heroku
THEN the user should have proper build scripts for a webpack application
```

## Mock-Up

The following images show the application's appearance and functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)


## Development Technologies Used




  * Uses IndexedDB to create an object store and includes both GET and PUT methods

  * The application works without an internet connection

  * Automatically saves content inside the text editor when the DOM window is unfocused

  * Bundled with webpack

  * Create a service worker with workbox that Caches static assets

  * The application should use babel in order to use async / await

  * Application must have a generated `manifest.json` using the `WebpackPwaManifest` plug-in

  * Can be installed as a Progressive Web Application


* Application deployed to Heroku at live URL with build scripts


* Repository contains quality README file with description, screenshot, and link to deployed application

