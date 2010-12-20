#IE6 Upgrade Warning

![Example Screenshot](http://img683.imageshack.us/img683/3734/exampleuk.png)

NOTE: This is based off http://code.google.com/p/ie6-upgrade-warning/. Thanks to him for a great script, I've taken it further so that people can localize the messaging into different languages.

The ie6-upgrade-warning is a little script (7.9kb) that displays a warning message politely informing the user to upgrade the browser to a newer version (links to newest IE, Firefox, Opera, Safari, Chrome are provided).

The webpage is still visible behind a transparent background, but access to it is prevented. The idea is to force users to upgrade from IE6 and avoid the website from a bad reputation that website is not rendering correctly in IE6.

Provides a much more sane way of localization.

## Usage 

Look at the index.html file for example. This is a work in progress, as I'm refactoring someone else's code.

## Changelog

* Fixed JS Lint errors
* Parameterized configObj so that you can set an imgPath as well as localizations lookup object

##Contributers

renatocarvalho