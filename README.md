# 35-3-object-oriented-node-pg-exercise



Install the required node modules: 

`$ npm install` 

Start the server with nodemon
Take a tour of the site at http://localhost:3000 

Configuring nodemon for templates

By default, nodemon will not listen for changes to .html files. This means that when you start editing your templates, you’ll need to manually stop and start your server in order to see your changes take effect.

To fix this, you can tell nodemon what extensions to watch with the -e flag. For this assignment, it’s worth telling it to listen for changes to HTML, CSS, and Javascript, so you should start your server with the following command:

`$ nodemon -e js,html,css`
