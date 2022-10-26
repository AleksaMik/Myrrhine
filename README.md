# Myrrhine


## Description

The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection.  This application allows the user to access visited pages even if the application is offline.

## Technical Criteria

Uses IndexedDB to create an object store and includes both GET and PUT methods

The application works without an internet connection

Automatically saves content inside the text editor when the DOM window is unfocused

Bundled with webpack

Create a service worker with workbox that Caches static assets

The application should use babel in order to use async / await

Application must have a generated manifest.json using the WebpackPwaManifest plug-in

Can be installed as a Progressive Web Application

## Screenshots of the aplication

<img width="1787" alt="Screen Shot 2022-10-25 at 2 59 35 PM" src="https://user-images.githubusercontent.com/105229148/197881951-81ad7404-fc5d-4373-81be-9e4967646031.png">

<img width="1792" alt="Screen Shot 2022-10-25 at 3 00 19 PM" src="https://user-images.githubusercontent.com/105229148/197881971-c0dc459d-8b2f-46ce-883e-0907d1b39afb.png">

<img width="1786" alt="Screen Shot 2022-10-25 at 3 45 57 PM" src="https://user-images.githubusercontent.com/105229148/197881981-61947001-0431-42ac-b098-54116038e5ff.png">


<img width="1783" alt="Screen Shot 2022-10-25 at 3 49 27 PM" src="https://user-images.githubusercontent.com/105229148/197881998-b0726e06-5d9b-48b6-9db2-f4799b574ab3.png">

<img width="180" alt="Screen Shot 2022-10-25 at 3 50 18 PM" src="https://user-images.githubusercontent.com/105229148/197882009-3e5aa101-7b3b-48f2-b429-2583dd2a6cde.png">


## Installation

*  This application will use the following npm packages:-

         * npm install express (express.js)
         * npm install --save-dev webpack (Webpack)
         * npm install webpack-dev-server --save-dev (webpack-dev-server)
         * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
         * npm install babel (Babel)
         * npm install --save-dev css-loader (CSS-loader)
         * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
         * npm install idb (IndexedDB)

## Deplyments 
- Application deployed to Heroku at live URL with build scripts
- Application loads with no errors
- Application GitHub URL submitted
- GitHub repo contains application code
## Links

[URL of the GitHub repository](https://github.com/AleksaMik/Myrrhine)

[demo-video](https://drive.google.com/file/d/1_dQ7DOtfShJWYLaZzbcF_CRUfAMSqnxj/view)

 [Heroku URL of the deployed application]()
 
