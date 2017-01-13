# White Label Agency
> Test makeup :)

## Features
- CSS Autoprefixing
- Automagically compile Sass with libsass
- Automagically lint your scripts
- Map compiled CSS to source stylesheets with source maps
- Image optimization
- ES2015 features by using Babel
- ES6 Modules && Tree-Shaking with [rollup.js](http://rollupjs.org/)
- Multiple bundles
- JADE templates
- Errors notification
- All configs && paths in one place

## Getting Started
- Clone this repo
- ```npm install -g gulp```
- ```npm install```
- ```bower install```
- ```bower install foundation-sites```
- run ```gulp```

## Gulp Tasks
- ```gulp```
    - Start ```gulp build``` && add watch
- ```gulp build```
    - Rebuild all project files
- ```gulp clean```
    -   Remove ```/dist``` directory
- ```gulp js:build```, ```gulp style:build```, ```gulp html:build```, ```gulp fonts:build```, ```gulp images:build``` for selective build

## Settings
All project path you can find in ```gulp/path.js```. Just add you folder in ```srcDir``` and ```publicDir``` and start to work :)

All plugins config with link to npm you can find in ```gulp/config.js```


## Pages
- https://akopean.github.io/Whte-Label-Agency/Blog.html
- https://akopean.github.io/Whte-Label-Agency/Home.html
- https://akopean.github.io/Whte-Label-Agency/Contact.html	
- https://akopean.github.io/Whte-Label-Agency/post.html
