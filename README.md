# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


////////

Way to install Vite
    npm create vite@latest
    select project name
    select framework
    select language 

Will show a message as below:
    "Scaffolding project in /home/project/learning_react...

    Done. Now run:

        cd learning_react
        npm install
        npm run dev

Deploying GitHub pages

    npm install gh-pagas --save-dev

In json file is need add below lines, just befor "build": "vite build"

    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist",   

Go to vite.config.js file and type below line, just befovre plugins...

    base: "/repository_name",

Type below code to run the page

    npm run deploy