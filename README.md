#Barebones WordPress Developer Base Theme - Sass Edition

Thank you for choosing to use Barebones, a completely stripped down "starter theme" for WordPress designers and developers.

It has been organised and optimised to give you the minimum markup and CSS (Sass) required to start building your own awesome designs.

##No assumptions or frameworks

Barebones makes no markup or layout choices for you like other frameworks and the CSS doesn't assume you need a specific grid or styles. That's for you to add on top of the basic structure that's been set up.

##Things you need to check or change

* The theme is bundled with a call to the latest jQuery at the time of release, you may need to update this (or roll back to a V1.x.x release if you need to support less than IE9)
* Update the Favicon and Apple Touch Icon graphic to your own
* Check the paths in config.rb if you want to use a different folder structure
* /assets/sass/globals/_settings.scss has a few mixins and settings I find incredibly useful along with links to their sources and how to use them. If you don't need these, remove them

###Getting up and running

Copy the folder "sass-barebones" into your /wp-content/themes/ folder on your WordPress install. Make sure Node and Gulp are installed on your machine.  Then run the following command in your project directory to load project dependencies:

    npm install

After the installer finishes, you can tell Gulp to watch your files with the following command:

    gulp watch

Gulp is pre-configured in this project to compile your Sass, concatenate and minify your Javascript, and optimize your images whenever changes are sensed in the corresponding files.  For more information on getting set up with Gulp, see <http://travismaynard.com/writing/getting-started-with-gulp>

####Help and Support
Please direct any post any support questions or indeed ways this can be improved and I'll be happy to help out as best I can.

Thanks

James.
@welcomebrand
