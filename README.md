# Floating Space Man

> Using Backbone, HTML5 Canvas and CSS3 Animations

> DEMO: <a href="http://mduplinsky.me/projects/floating-space-man/">http://mduplinsky.me/projects/floating-space-man/</a>

## Usage

> SASS

`$ [sudo] gem install sass`

`$ cd floating-space-man`

First run `$ touch styles.scss styles.css`

`$ sass --watch styles.scss:styles.css --style compressed` compressed will minify on un-watch

When done:

`Ctrl+C` via Terminal to exit watch

> UglifyJS 2

`$ [sudo] npm install uglify-js -g`

To uncompress `main.min.js`

`$ uglifyjs main.min.js -b -o main.js`

To compress & mangle `main.js`

`$ uglifyjs main.js -c -m -o main.min.js`

> Vendor.js

Includes

`SIZZLE - A pure-JavaScript CSS selector engine designed to be easily dropped in to a host library.`

`Backbone.js`

`jQuery Waypoints`

`jQuery TimeAgo Plugin`

`jQuery Easing Plugin`