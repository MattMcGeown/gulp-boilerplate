# gulp-boilerplate
We all know what a boilerplate is. I created this to get me up and running with my gulp projects without the hassle of recreating my base files.

### Requirements
- [NodeJS](https://nodejs.org/en/)
- [gulp](https://gulpjs.com/)
- [gulp-sass](https://www.npmjs.com/package/gulp-sass)
- [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer)
- [gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin)
- [gulp-plumber](https://www.npmjs.com/package/gulp-plumber)
- [gulp-rename](https://www.npmjs.com/package/gulp-rename)
- [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)
- [browser-sync](https://browsersync.io/)

### Usage
Clone the repo and run **npm install** in the command line
SASS/SCSS should go into [app/scss/sections](https://github.com/mypixels/gulp-boilerplate/tree/master/app/scss) and be imported into [app/scss/style.scss](https://github.com/mypixels/gulp-boilerplate/tree/master/app/scss/style.scss)


The [gulpfile.js](https://github.com/mypixels/gulp-boilerplate/blob/master/gulpfile.js) is setup to:
- Minify all SASS and SCSS into [app/css/style.min.css](https://github.com/mypixels/gulp-boilerplate/blob/master/app/css/style.min.css)
- Minify all JavaScript files inside [app/js/](https://github.com/mypixels/gulp-boilerplate/tree/master/app/js)
- Compress all images inside [app/img](https://github.com/mypixels/gulp-boilerplate/tree/master/app/img) without lowering quality
- Feed everything to [browser-sync](https://browsersync.io/) for live refresh
- Watch all CSS / HTML / JS files for changes and live refresh after each file save

The boilerplate is based on a mobile first design basis with media queries already in place using mixins in [app/scss/base/_base.sass](https://browsersync.io/https://github.com/mypixels/gulp-boilerplate/blob/master/app/scss/base/_base.sass)
