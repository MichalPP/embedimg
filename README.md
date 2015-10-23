# embedimg
Embed images into html/css/js

this command takes standard input (a html/css/js file) and includes all image references as base64 data. output is to standard output.

the only parameter is prefix to add to your images (usually something like http://www.oma.sk/img )

typical usage:
edited.html | php embedimg.php 'http://www.oma.sk' > final.html
edited.css | php embedimg.php 'http://www.oma.sk'| your-favorite-css-minimazer > final.css

see https://en.wikipedia.org/wiki/Data_URI_scheme for specification
