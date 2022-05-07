# 19 Progressive Web Applications (PWA): Text Editor

## Live Links
[GitHub Repo](https://github.com/Morganbb104/HW_19-Progressive-Web-Applications-PWA-Text-Editor)  
[Deployed Aplication](https://dashboard.heroku.com/apps/pwa-texteditior-0506)

## About

This is a simple Progressive Web App (PWA) named text editor. This app uses both IndexedDB and Localstorage for persistent data.
The application will first search for data stored in indexedDb, but if there is no result then it will move in localStorage to populate the editor when it is loaded. As a PWA, this app is also capable to operate offline and save data locally on the user's devices.
This app is a handy tool if users just need to quickly write down a code idea or snippet, or users don't have acces to another text editor.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```
## Usage

To use the app, simply follow the link below to the deployed app. To install locally, click the 'install' button in the navbar.


## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

