# Clarifying Cancer
Website for Sarah Auvil

#Installation:

To work on the project locally, please refer to the "src/app" folder instead of the build folder. This segments each piece out in a more granular fashion.

The first thing you'll need to do will be to install the dependencies, as these are listed under gitignore. So run:

`npm install`

Then, because we're using bower to handle build dependencies, run:

`bower install`

Finally, upon making all the changes you want to make, you'll need to rebuild the deployment folder. We're using Gulp on this project to handle concatentation, minification, compression, and compilation. All you have to do is run:

`gulp`

And it will handle all the HTML, CSS, JS, images, fonts, and clean tasks necessary to rebuild.

As of this writing, to view changes, you'll have to open the HTML file in your browser.

Adjustments to this process to come later.
