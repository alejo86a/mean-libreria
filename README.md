# mean-libreria

A small MEAN-stack (MongoDB, Express, AngularJS, Node.js) practice project: a CRUD application to insert, list, and delete books in a "library" (librería).

> From the original `package.json` description: *"intento de aplicacion MEAN donde se hace un crud para insertar, borrar y mostrar los libros de una libreria"* ("attempt at a MEAN app that does CRUD to insert, delete and show books from a library").

## Tech stack

- **Backend:** Node.js, Express, MongoDB (native driver), body-parser
- **Frontend:** AngularJS, served as static files by Express

## Project structure

- `server.js` – Express server entry point
- `server/controllers/bookCtrl.js` – book CRUD controller (find all, add, delete)
- `app/` – AngularJS front-end app (controllers, templates)
- `index.html` – app shell

## Running it

```bash
npm install
node server.js
```

The server listens on `process.env.PORT` (default `3000`) and expects a MongoDB connection for the book data endpoints.

## Context

This repository is a **fork** of [cposada23/mean-libreria](https://github.com/cposada23/mean-libreria). It is a personal learning/practice exercise with the original author's commits; this fork does not add any additional commits of its own on top of the upstream repository.
