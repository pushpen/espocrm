<a href='http://www.espocrm.com'>EspoCRM is an Open Source CRM</a> (Customer Relationship Management) software that allows you to see, enter and evaluate all your company relationships regardless of the type. People, companies or opportunities - all in an easy and intuitive interface.

Download the latest release from our [website](http://www.espocrm.com).

### How to report bug

Create an issue [here](https://github.com/espocrm/espocrm/issues) or post on our [forum](http://forum.espocrm.com/bug-reports?routestring=forum/bug-reports).

### How to get started (for developers)

1. Clone repository to your local computer.
2. Change to the project's root directory.
3. Install [composer](https://getcomposer.org/doc/00-intro.md).
4. Run `composer install` if composer is installed globally or `php composer.phar install` if locally.

Never update composer dependencies if you are going to contribute code back.

Now you can build.

If your repository is accessible via a web server then you can run EspoCRM by url `http://PROJECT_URL/frontend` w/o making a build. To get a proper data/config.php and data in a database you can run /install via browser.

### How to build

You need to have nodejs installed.

1. Change to the project's root directory.
2. Install project dependencies with `npm install`.
3. Run Grunt with `grunt`.

The build will be created in the `build` directory.

### License

EspoCRM is published under the GNU GPLv3 [license](https://raw.githubusercontent.com/espocrm/espocrm/master/LICENSE.txt).
