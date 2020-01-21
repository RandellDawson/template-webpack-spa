# Basic SPA Webpack Starter Template

This is a basic Webpack SPA project template for a web app written in ES6 & CSS.

This assumes you have a directory structure as follows:

```
package.json
webpack.config.js
src/
  index.js
  index.html
  style.css
```

---

## Installation

**1. Clone the repo and start your own:**

```sh
git clone https://github.com/RandellDawson/template-webpack-spa.git
rm -rf .git
git init
```

**2. Install dependencies:**

```sh
npm install
```

## Development Workflow

**Start the live-reload dev server:**

```sh
npm run dev
```

Open up http://localhost:8080/webpack-dev-server/ to see your app.
The app gets reloaded as files change.

## Deployment Workflow

To deploy your static app, upload the contents of `dist/` to a web server.

`http-server` is used to serve the files in `dist/`.