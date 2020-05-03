my portfolio website

The way I have this set up is:

PROJECT FOLDER:

  -dist: //when we run npm run sass and npm run babel, our es6 and sass files get compiled into here.
    --script-comp.js
    --main.css
    --index.html
    
  -scss: //our sass code goes here
    --main.scss
    
  -js: //our es6 javascript code goes here
    --script.js

to initialize all the stuff you need:

In the main directory
1. npm install node-sass
2. npm install --save-dev @babel/core @babel/cli

We will be writing our code in sass and ES6 javascript in the js folder and scss folder. Lastly our 
HTML will just be in the index.html file. To compile our SCSS files we do "npm run sass", to 
compile our ES6 code we do "npm run babel" (the commands that are going to run are specified in our
package.json file)
