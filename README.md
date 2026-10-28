# Node.js & Express Exercises

A freeCodeCamp exercise workspace for learning server-side JavaScript and Express. The repository contains the lesson runner and a minimal application in which to implement the exercises.

## Tech stack

Node.js · Express · freeCodeCamp exercise runner

## Structure

- [myApp.js](myApp.js) creates and exports the Express application.
- [server.js](server.js) starts the lesson runner and HTTP server.
- `public/` and `views/` contain the starter assets.

The custom application is currently a starter scaffold without its own API routes.

## Run locally

Use Yarn with the committed lockfile.

```sh
yarn install --frozen-lockfile
yarn start
```

The server uses `PORT` when configured, otherwise port 3000. Keep the verification runner in `server.js` intact when implementing lessons.
