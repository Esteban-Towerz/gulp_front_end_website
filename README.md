# Using Gulp to Build a Front End Website
You’ll be required to set up a Gulp build process to prepare the website for deployment.

@Esteban-Towerz -- @milestake :love_letter: :+1:

<img width="1164" alt="screen shot 2017-10-01 at 6 33 07 pm" src="https://user-images.githubusercontent.com/25851867/31060333-5cf32866-a6d7-11e7-9004-19c5791c8ea6.png">


## User Stories:
### to get the requested Minimum Viable Product:

- [x] As a developer, I should be able to run the `npm install` command to install all of the dependencies for the build process.

- [x] As a developer,  I should be able to run the `gulp scripts` command at the command line to concatenate, minify, and copy all of the project’s JavaScript files into an all.min.js file that is then copied to the dist/scripts folder.

- [x] Source maps will be generated. Also, all of the project’s JavaScript files will be linted using ESLint and if there’s an error, the error will output to the console and the build process will be halted.

- [x] As a developer,  I should be able to run the `gulp styles` command at the command line to compile the project’s SCSS files into CSS, then concatenate and minify into an all.min.css file that is then copied to the dist/styles folder.

- [x] As a developer, when I run the `gulp scripts` or `gulp styles` commands at the command line, source maps are generated for the JavaScript and CSS files respectively

- [x] As a developer,  I should be able to run the `gulp images` command at the command line to optimize the size of the project’s JPEG and PNG files, and then copy those optimized images to the dist/content folder.

- [x] As a developer,  I should be able to run the `gulp clean` command at the command line to delete all of the files and folders in the `dist` folder.

- [x] As a developer,  I should be able to run the `gulp build` command at the command line to run the `clean`, `scripts`, `styles`, and `images` tasks with confidence that the `clean` task completes before the other commands.

- [x] As a developer,  I should be able to run the `gulp` command at the command line to run the "build" task.

- [x] As a developer,  I should be able to run the `gulp serve` command on the command line build and serve the project using a local web server.

- [x] As a developer,  I should be able to run the `gulp watch` command, the `script` task should run and the current page should be reloaded in the browser when a change is made to any JavaScript (*.js) file.

## Extra Credit

- [x] As a developer, when i run the `gulp scripts` command at the command line, all of my project’s JavaScript files will be linted using ESLint and if there’s an error, the error will output to the console and the build process will be halted.