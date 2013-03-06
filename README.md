# The Foundation Theme

The Foundation theme is built using [Foundation 4](http://foundation.zurb.com/) (a CSS and Javascript framework) on top of the [Statarkers](http://statamicthem.es/themes/statarkers-theme) theme for Statamic. Foundation 4 offers an excellent starting point for building responsive websites and the Statarkers theme offers a base set of files for building Statamic themes quickly and efficiently.

The two work together to help you create a responsive website with a blog in minutes. The theme has been kept as simple as possible so that it can form a base to build off. Feel free to use it in your projects.

##Installing

To install the theme follow the instructions below.

1. [Install Statamic:](http://statamic.com/docs/getting-started/installing-and-updating) **Don't forget to set up your .htaccess file**.
2. Copy the foundation-4 theme folder to your _themes folder. Please note if you have downloaded the foundation-4-master folder **the foundation-4 theme is located inside the _themes folder**.
3. Delete the contents of your Statamic install fieldsets folder then copy the new fieldsets from the foundation-4-master folder (located in _config/fieldsets).
4. If you would like to use the dummy content provided with the foundation-4 theme (recommended) then delete the contents of your existing _content folder and copy the files and folders from the foundation-4-master _content folder.
5. In your Statamic install go to _config settings YAML file and change the _theme name from denali to foundation-4. If this is a clean install you should also change the site name and url to whatever you are using. We suggest also changing the _taxonomy_slugify to true as this gives you cleaner url's.
6. If you are going to add any additional styles make sure that you have the zurb-foundation gem installed and start watching the foundation-4 theme directory using the compass watch command. The [Foundation 4 Documents](http://foundation.zurb.com/docs/sass.html) explain how to set this up if you are unsure.
7. All user styles should be added to the _app.scss file (located in the sass folder).
8. Any user JavaScripts should be added to the foundation-4.js file located in the js folder.