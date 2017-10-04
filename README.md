Customizing a Bootstrap SASS build with Bower
=============================================

Eerst in de juiste DIR: 

npm install gulp --save-dev

npm install bower --save-dev OF in GIT console: bower install

in GIT console in de juiste map: bower install bootstrap#v.4.0.0-alpha.6

pas evt. iets aan in root/css/_variables.scss ...

gulp



Troubleshooting
---------------

If your node version is 4 and you are using gulp-sass, then try

npm uninstall --save-dev gulp-sass

npm install --save-dev gulp-sass@2

Verdere bronnen
---------------
http://getbootstrap.com/docs/4.0/getting-started/contents/
