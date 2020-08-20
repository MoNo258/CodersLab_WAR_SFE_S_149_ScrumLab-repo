# ScrumLab
This is a repository dedicated to ScrumLab front-end project in Coders Lab IT School. This project was realized together with the team up until point this repo was created. We worked in `Scrum methodology`, our sprint for this project took 1 week. We used `Trello` for tracking progress (`Kanban board`). Our team kept repository on GitHub and members worked on their tasks on separate, local branches. `WebStorm` was used to merge changes (locally) with origin/master. Then `GitHub` was used for pull requests and final merge with master (after approval from another team member).

After sprint was finished (starting from the moment when this repo was created) project was developed by MoNo258.

#### This project uses:
* `Sass Dart`
* `JavaScrip ES6`
* `Gulp` (for Sass)
* `Webpack` (for js)

#### This project was created:
* in `Scrum` methodology
* using `GitHub` repo and `Git` for local branches
* using `Trello` (`Kanban board`) for tracking progress
* using `WebStorm`

## Project: Landing Page and App

This project assumed creation of Landing Page and App related to organizing meals recipes and schedules of such meals for the user who registered herself/himself in the app (onetime registration with name saved in `localStorage`).

## How to start
To start development follow this instruction:

* `clone` this repo
* `npm install` all necessary npm packages


## Gulp usage
Available commends for you to type in console:

`gulp` - this will run gulp in browserSync mode, that means gulp will start server on your `localhost` and refresh it for you everytime you change `scss`, `js` or `html` file. Using this command will do all the work for you :) Gulp runs in watch mode, that will compiles your `main.scss` into `css/main.css` & auto-inject into browsers.
 To see proper page result you must copy `development/images` into `dist/images`.


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
