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

## Contributers

- [renatocarvalho](https://github.com/renatocarvalho)

## License

The MIT License (MIT)

Copyright (c) 2013 Mihai Ile

Copyright (c) 2013 Jaime Bueza

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
