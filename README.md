camunda BPM Homepage
====================

This repository contains the sources of the [camunda BPM homepage](http://camunda.org).

The page is built using the [DocPad web framework](http://docpad.org) for site generation
and [Grunt](http://gruntjs.com) for minify operations.


Overview
--------

The `site/src/` folder contains the sources for the website.

The `dev/` folder contains utilities for development.


Start hacking
-------------

In order to start hacking the camunda.org homepage, you first need to setup DocPad and Grunt.

1. Install [node.js](http://nodejs.org/).
2. Open a terminal, navigate to the `site/` folder and type `npm install`.
3. Install [grunt-cli](http://gruntjs.com) globally with `npm install -g grunt-cli`.
4. Run DocPad using `./node_modules/.bin/docpad run` or install docpad via `npm install -g docpad` if you want to have it globally available in your path.
5. Open a second terminal, navigate to the `site/` folder and type `grunt`.
4. Go to [http://localhost:9778/](http://localhost:9778/).

Have fun.


License
-------
![CC BY-SA](http://i.creativecommons.org/l/by-sa/3.0/80x15.png)
The content on this project is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).