# react-to-gihub-pages

Steps:
1. install github-pages in terminal (npm i gh-pages --save-dev)
2. goto package.json in your project folder
3. add this command above the "name" key ("homepage": "https://github_username_goes_here.github.io/",)
4. Add deployment scripts to the package.json file in the scirpts file example underneath
4.5.: 
"scripts": {
+   "predeploy": "npm run build",
+   "deploy": "gh-pages -d build",
    "start": "react-scripts start",
    "build": "react-scripts build",
}

5. npm run deploy
