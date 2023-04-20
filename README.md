# UTA-Bootcamp-Challenge19
## Progressive Web Applications (PWA) Challenge: Text Editor
----------------------------------------------------------------------
## Description

This application is a browser-based text editor that adheres to the PWA standards and is designed as a single-page application. It provides various data persistence techniques to ensure redundancy in case any option is not supported by the browser. Moreover, the app can work offline as well.

----------------------------------------------------------------------

## User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

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
* "User Story" & "Acceptance Criteria" listed above have been provided by the UTA Bootcamp Program 2022.
----------------------------------------------------------------------

## Table of Contents

- [Installation](#installation)
- [Built Using](#built-using)
- [Preview](#preview)
- [Credits](#credits)
- [Links](#links)
- [License](#license)

----------------------------------------------------------------------

## Installation

1. Clone/download git repository.
2. Run command "npm i"
3. Run command "npm run start" to open app on live server.

#

## Built Using

- Node.js
- Express.js
- NPM Packages:
    - npm i idb
    - npm i if-envv

#

## Preview

<img src= "assets/images/C19 Screenshot 1.png"/>
<img src= "assets/images/C19 Screenshot 2.png"/>

## Credits

This project was worked on in collaboration with:
- Erin Peifer: https://github.com/Airen22
- Code template credits: UTA Coding Bootcamp Repo

## Links

- Heroku Deployment Link: https://uta-texteditor-app.herokuapp.com/ 
- GitHub Repository Link: https://github.com/khevb27/UTA-Bootcamp-Challenge19 

----------------------------------------------------------------------
## License

Please refer to licensing documentation in the project repository.

<img src="https://img.shields.io/badge/license-MIT License-blue.svg" alt="GitHub License">

----------------------------------------------------------------------
