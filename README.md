# front-end-boilerplate
Modern, optimised, minimal front end boilerplate; installed and kept up to date via PNPM.

Will play nice(st) with the latest versions of modern browsers:-
* Edge
* Firefox
* Chromium
* Safari

## Get started
* git clone https://github.com/Kry-dev/smartbot.github.io.git
* cd SmartBot
* npm install -g pnpm
* pnpm install
* gulp
* Start building!

## Features

### Javascript
* Bootstrap v5.3.3
* Fully vanilla, no frameworks here!
* Javascript scripts process (uglify, compression, concat)
* Webpack via Gulp watch task runner for modular imports
* Native deferred loading of JS

### CSS
* Bootstrap v5.3.3
* SASS styles process (compression, concat)
* PurgeCSS to rid of bloat and unused styles
* Critical for inlining of critical styles and deferred loading of non-critical styles

### Assets
* Handlebars HTML templating process (featuring partials)
* Imagemin IMG process (image optimisation and SVG minification)
* WebP conversion for imagery (optimised file size output)
* SVG icon sprite (generated inline from SVG assets)
* Sitemap.xml auto generated (using file creation/update date and time)
* BrowserSync process (auto reload on file save/update)
