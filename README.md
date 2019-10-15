Minify
======

The Minify module is designed to improve the speed at which pages on your
website will load. Pages can be rendered using minified versions of both
HTML and JavaScript files.

Minifed HTML and JavaScript has the code comments and whitespace removed, which
will help to reduce the overall file size. Smaller file size reduces the page
load time and improve the website performance.

Minified HTML is generated using regular expression, and Minified JavaScript
files are generated using GOOGLE Closure Compiler webservice.

Please be aware that Closure Compiler has throttling limits. If your website
has a lot of JavaScript files, you may need to start the minifying process a
few separate times, with one hour between each attempt.


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Visit the Performance settings page under Administration > Configuration >
  Development > Performance (admin/config/development/performance) and
  enter the required information.

- To generate and manage minified JavaScript files, select the
  Minify JavaScript Files tab at the top of the page.

Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/minify/wiki/Documentation.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/minify/issues.

Current Maintainers
-------------------

- Jen Lampton (https://github.com/jenlampton).
- Seeking additional maintainers

Credits
-------

- Ported to Backdrop CMS by [Jen Lampton](https://github.com/jenlampton).
- Originally written for Drupal by [Atul Bhosale](https://www.drupal.org/u/atulbhosale).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

