# JATE "Just Another Text Editor"

## Description

J.A.T.E is a locally installable Progressive Web Application (PWA) that operates in the browser offline. This program uses a variety of data persistence strategies to ensure that it functions on all supported browsers. The idb software and an IndexedDB database are used by J.A.T.E. You can access this application in production by reading the docs; it has been deployed to Heroku!


## Table of Contents
1. [Description](#description)
2. [Table of Contents](#table-of-contents)
3. [User Story](#user-story)
4. [Acceptance Criteria](#acceptance-criteria)
3. [Usage](#usage)
4. [Installation](#installation)
5. [License](#license)

### User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria 

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Usage

LIVE URL: [https://bryce-text-editor-122cc371db37.herokuapp.com/](https://bryce-pwa-text-editor-6035a2b7f477.herokuapp.com/)

![Just Another Text Editor](text-editor.png)

This application can also be installed to run in a separate window because it is a PWA.

## Installation

There are several setup stages because this program uses both a client and a server. Initially, execute "npm i" to install "concurrently," enabling the subsequent script "npm install" to function flawlessly. Installing all required npm dependencies for the client and server will enable the program to function. To begin development, just type "npm run start:dev," and to begin production, just "npm start."

You can also install the app from the browser once it has been deployed by using the installation icon in the address bar or the "Install" button on the page. This will launch the text editor on a separate screen.

## License
MIT
