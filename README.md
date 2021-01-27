# VueJS Vuetify Vue Router Vuex - Basic Project Skeleton

## Getting started

This is a basic VueJs, Vuetify, Vue Router and Vuex skeleton written on JavaScript using async/await. Great for building a starter web app.

This project is created to help other developers create a **basic VueJS app in an easy way**. This basic example shows how powerful and simple JavaScript and VueJS can be. Do you want to contribute? Pull requests are always welcome to show more features.

## This is the DPY & YAC frontend for Data Collaboration

Hi! I'm Bruno Borges, and this is the Final Guided project at CCT.

The project has been forked from Daniel Avellaneda, the creator and maintainer of [node-express-mongodb-jwt-rest-api-skeleton](https://github.com/davellanedam/node-express-mongodb-jwt-rest-api-skeleton/blob/master/README.md) and [vue-skeleton-mvp](https://github.com/davellanedam/vue-skeleton-mvp/blob/master/README.md)

These projects are a "starter web app kit" for any developer who wants to build their own app without starting from scratch: API + Frontend

Both projects have been downloaded thousands of times by web developers around the world.

## Features

-   Vuetify
-   Multiple environment ready (development, production).
-   Vue router
-   Vuex
-   i18n ready.
-   Google Analytics ready.
-   Ready to add to home screen in iOS and Chrome, checks if there´s an app update every 2 hours and reloads page (When a web app is added as stand alone there´s no reload button in the browser so new .js files from a new build never get loaded)
-   Landing page.
-   Protected home page.
-   Login.
-   Signup.
-   Forgot password.
-   Account verification.
-   User profile.
-   Users admin area with CRUD operations.
-   Cities admin area with CRUD operations.
-   Testing with Cypress and mocha/chai.
-   NPM script for keeping good source code formatting using prettier and ESLint.
-   Use of ESLint for good coding practices.
-   Use of prettier for beautiful format.
-   Ability to refresh token
-   JWT Tokens, make requests with a token after login with `Authorization` header with value `Bearer yourToken` where `yourToken` is the **signed and encrypted token** given in the response from the login process.

## Demo

A demo of this Frontend is located at: <https://console.cloud.google.com/home/dashboard?project=electric-autumn-290920&folder=&organizationId=>

### Login credentials

email: `admin@admin.com`  
password: `12345`
email: `dpl@dpl.com`  
password: `12345`
email: `yac@yac.com`  
password: `12345`

Repo is here: <https://github.com/borgesdesa/>

## How to install

### Using Git (recommended)

1.  Clone the project from github. Change "myproject" to your project name.

```bash
git clone https://github.com/borgesdesa/frontend ./frontend
git clone https://github.com/borgesdesa/backend ./backend
```

### Install npm dependencies after installing (Git or manual download)

```bash
cd frontend
npm install
npm update
```

## VERY IMPORTANT

This project uses Vue Router HTML5 History Mode, this means when you are in development mode you can hit Cmd+R (mac) or F5 (Windows) to reload the page and it will work, but when the project is built you will have problems, so will need to do a small change in your web server to make that work. Please read the official Vue Router documentation here: <https://router.vuejs.org/guide/essentials/history-mode.html#example-server-configurations>

### Compiles and hot-reloads for development

```bash
npm run serve
```
