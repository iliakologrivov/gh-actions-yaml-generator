# Ghygen
__Ghygen__ is a GitHub actions Yaml Generator.

For Laravel/PHP Developers, __Ghygen__ allows you creating your __Yaml__ file for __GitHub Actions__, so you can:

- select events trigger (manually , on push, on pull request);
- select branches;
- enable caching for all vendors;
- enable caching PHP packages;
- select multiple PHP versions;
- select Node version for NPM (npm run something);
- caching node packages;
- setup Mysql service;
- run migrations;
- execute tests via phpunit;
- static code analysis; 
- code sniffer (via phpcs);
- validate Yaml file.

This is a Work In Progress, we are adding new features...

## Usage
Follow these steps:
- open the browser to the URL: https://iliakologrivov.github.io/gh-actions-yaml-generator/
- fill the form;
- copy the content of your generated Yaml in a new file in your Laravel project _.github/workflows/laravel_workflow.yaml_ .
- commit and push the new file.

If you configured "On - Push" you will see the running Actions in your Actions section of your GitHub project.
