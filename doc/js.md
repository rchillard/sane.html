[sane.html](github.com/rchillard/sane.html) | [Table of Contents](README.md)

# JavaScript

Information about the default JavaScript included in the project.

## main.js

This file can be used to contain or reference your site/app JavaScript code. 

## plugins.js

This file can be used to contain all your plugins.

By default the `plugins.js` file contains a small script to avoid `console`
errors in browsers that lack a `console`. The script will make sure that, if a
console method isn't available, that method will have the value of empty
function, thus, preventing the browser from throwing an error.

## vendor

This directory can be used to contain all 3rd party library code.
