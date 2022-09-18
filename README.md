# pwa-text-editor

## Table of contents

- [Overview](#overview)
  - [Deployed link](#deployed-link)
  - [The challenge](#the-challenge)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Video Walkthrough](#video-walkthrough)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Deployed Link
https://k3vbot-jate.herokuapp.com/

### The challenge

```
Finish the code to create a test editor that works offline using manifest and service workers. 
```
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


### Screen Shots

indexDB
![idb](https://user-images.githubusercontent.com/102929793/190880565-e97144c5-7363-4be8-92cf-075c8c28b962.png)



Text while offline
![Offline-service-worker](https://user-images.githubusercontent.com/102929793/190880576-f6d40b96-9d32-4e6b-b777-7e7ad040146b.png)




### Built with

- express
- Webpacks
- Babel
- idb

### Continued development

Fix the install button. 

## Author

https://github.com/k3vbot
