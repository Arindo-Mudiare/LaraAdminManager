## About Lara Admin Manager

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

## Learning Laravel

-   first run npm install
-   run php artisan make:auth
-   run migration
-   create demo user admin
-   create master.blade.php file in layout directory
-   copy source code of admin lte 3 starter into master.blade.php
-   "http://demo.cssmoban.com/cssthemes5/cpts_992_bmf.0-alpha/starter.html"
-   replace js and css with public folder app.css and app.js
-   then point home page to use new master.blade layout
-   add the following lines to the resources/js/app.js -- require('admin-lte');
-   add the following lines to the resources/sass/app.scss -- @import '~admin-lte/dist/css/adminlte.css';
-   run npm run watch to compile assets
-   install font awesome sass via npm

-   then paste \$fa-font-path: "../webfonts"; in app.scss
-   @import "~@fortawesome/fontawesome-free/scss/fontawesome.scss";
-   @import "~@fortawesome/fontawesome-free/scss/solid.scss";
-   @import "~@fortawesome/fontawesome-free/scss/brands.scss";
