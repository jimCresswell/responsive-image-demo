# Responsive layout

A demo so I can play with responsive layouts and responsive images.

## Development requirements
* Install [Node](http://nodejs.org/) and npm (comes with node).
* Install Gulp globally with npm.
  * `npm install -g gulp`
* Chrome installed or fiddle with Gulp 'serve' options to launch the browser of your choice.

## To launch locally
* Clone.
* Change to the cloned directory.
* `npm install`.
* Gulp.

## Notes
* See comments in HTML and CSS.
* Images optimised with https://imageoptim.com/ .
* Once iOS Safari supports the w attribute in srcset (http://caniuse.com/#feat=srcset) more logic can be added to load larger resolution images for wide screens. This could be done now now with backgroud images but then mobile devices would always
have to download about 2MB of images.