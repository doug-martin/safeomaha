# SafeOmaha

A HackOmaha project

# Twitter Bootstrap

The compiled Twitter bootstrap code is contained within the web/bootstrap directory. The source files are in web/less. Less is a "better" CSS language that uses node to compile down to pure CSS. To compile less, you will need Node and NPM installed, and then you will need to install the following node packages:

to install Node, please visit [http://nodejs.org](http://nodejs.org)

to install less

	npm install -g less

to install uglify-js

	npm install -g uglify-js

# heatmap

Heatmap is based off of a CGI port of gheat, a tool for drawing heatmaps based on google maps. it requires you to set up
mod\_rewrite and to allow .htaccess files to override things. This is designed to run with apache as a frontend.
