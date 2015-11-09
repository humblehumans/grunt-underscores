# grunt-underscore

[Grunt](http://gruntjs.com/) javascript task runner configured for [Wordpress](https://wordpress.org/) using [Automattic](https://github.com/automattic/) starter theme [Underscore](http://underscores.me/). Clone this repo into your theme folder and build locally. Theme will compile as 'humble-humans'.

```
$ npm install
$ bower install
$ grunt
```

- To update the theme with a new instance of [Underscore](http://underscores.me/) replace the contents of the 'src' folder. 

- Find and replace all instances of '../humble-humans' in 'Gruntfile.js' and replace with '../your-new-theme-slug'. If not using SASS, remove exclude statement '!style.css' from your [Grunt](http://gruntjs.com/) 'copy' task.

- When enabling theme make sure to activate the compiled version, both will appear in WP Admin theme panel. If using SASS differentiate the two by changing the name of your pre-compiled theme via 'src/style.css'.
