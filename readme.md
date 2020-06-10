# ScrumLab
This is a repository dedicated to ScrumLab front-end project in Coders Lab IT School. This project was realized together with the team up until point this repo was created. Starting from this moment project was developed by MoNo258.

## How to start
To start development follow this instruction:

* `clone` this repo
* `npm install` all necessary npm packages


## Gulp usage
Avaliable commends for you to type in console:

`gulp` - this will run gulp in browserSync mode, that means gulp will start serwer on your `localhost` and refresh it for you everytime you change `scss`, `js` or `html` file. Using this command will do all the work for you :) Gulp runs in watch mode, that will compiles your `main.scss` into `css/main.css` & auto-inject into browsers.


## Folder Structure
```
| - development/
	| - css/      
	| - fonts/
	| - images/  
	| - js/
	| - scss/
	| - app.html  
	| - index.html  
	| - recipes.html    
	| - schedules.html
| - dist/
| - package.json
| - gulpfile.js
| - webpack.config.js
```

***where:***
`dist` - stands for distribution and is used to contain optimized files for the production site (not available in this repo).
`development`  - is used to contain source code.
