# Darstellung von Meteo Daten

## Setup

### Prerequesites

Make sure to install [Visual Studio Code](https://code.visualstudio.com/) and the extension [Vetur](https://github.com/vuejs/vetur). The latter adds VueJS functionality to VS Code. Further, make sure to install [`yarn`](https://yarnpkg.com/en/) or [`npm`](https://www.npmjs.com/). Both are viable package manages for JavaScript, but we prefer the former.

### Download the code

First you need to download the code from GitHub.

```bash
git clone https://..
```

### Install all packages

Next, let `yarn` install all packages that are required to run the code base.

```bash
yarn install
```

### Getting started

After downloading the code and installing all packages, you can open the project in VS Code (File -> Open Folder; CTRL+K CTRL+O on Linux). Now open the Terminal (View -> Terminal) and type `yarn run serve`. This starts the application on your local machine and serves the web app on [http://localhost:8080](http://localhost:8080).

You are now ready to start coding. The project is set up such, that code gets formatted automatically when you save a file (STRG+S). This also reloads the part of the page that you have been working on in the web browser.

For example, we use double quotes `"` instead of single quotes `'` in the code base. If you use single quotes, VS Code will automatically replace them with double quotes, when you save a file.

## Project command reference

### Compiles and hot-reloads for development

```bash
yarn run serve
```

### Compiles and minifies for production

```bash
yarn run build
```

### Run your tests

```bash
yarn run test
```

### Lints and fixes files

```bash
yarn run lint
```
