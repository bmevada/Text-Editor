# Progressive Web Applications (PWA): Text Editor

Week 19: Progressive Web Applications (PWA) Challenge

## Summary

A text editor application has been built that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

In order to build this text editor, an existing application was used and implemented methods for getting and storing data to an IndexedDB database. A package called `idb` was used, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

This full-stack application has been deployed to Heroku.


## Deployed Links

[Link to deployed Heroku] https://secret-cliffs-64359.herokuapp.com/ 
[Link to Github] https://github.com/bmevada/Text-Editor.git

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
<img width="881" alt="mainpage" src="https://user-images.githubusercontent.com/109460560/206978439-23323af5-3157-488e-9f7b-260ec13a95b6.png">

<img width="404" alt="desktop application" src="https://user-images.githubusercontent.com/109460560/206978460-c12d73bb-256f-4d11-aafb-94baaf632bda.png">


The following image shows the application's `manifest.json` file:

<img width="1009" alt="manifest" src="https://user-images.githubusercontent.com/109460560/206978474-36eca987-8bfa-4668-af65-c37686bb2d06.png">


The following image shows the application's registered service worker:

<img width="1012" alt="service-workers" src="https://user-images.githubusercontent.com/109460560/206978485-f73860dc-9a3f-44c5-ae4b-dfd082cafb28.png">


The following image shows the application's IndexedDB storage:

<img width="1004" alt="ibd-storage" src="https://user-images.githubusercontent.com/109460560/206978498-8295fad5-78f1-42e2-b28b-8fa51284b24d.png">



## Development Technologies Used
 - nodemon
 - manifest.json
 - WebpackPwaManifest plug-in
 - Progressive Web Application
 - Heroku
 - ibd
 - babel



