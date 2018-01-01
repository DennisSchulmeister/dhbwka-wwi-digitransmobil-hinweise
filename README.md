lecture-slides.js Presentation Template
=======================================

Getting Started
---------------

This is the recommended project structure for a `lecture-slides.js` presentation.
Simply download this repository and start hacking it. It couldn't be easier. :-)

 * Download this repository (__Clone or download » Download ZIP__)
 * Extract anywhere on your computer
 * Install needed packages
 * Hack away

In order to install the needed dependencies open a terminal, cd to the directory
where this project lives and run the following command:

    $ yarn install

The project may contain as many presentations as you like. Each one of them is
just a HTML file in the `static` directory. See `static/index.html` for an example.
While you're writing you can use the built-in web server to run your slides:

    $ npm run devserver

This will run a web server, listening on http://localhost:8080

Uploading to a Web Server
-------------------------

Once you are done, build a static version and upload it to any web server:

    $ npm run build

If the files will live inside a directory on the web server (e.g. in `/slides/`),
don't forget to first edit the `package.json` file. Change this …

    "public_url": "",

to this:

    "public_url": "/slides/",

That's all. Now run the development server and have a look at the example slides.

Translations
------------

This example is in English. If you want to translate the User Interface, simply
edit the `index.js`. If is only a few strings.

Copyright
---------

`lecture-slides.js` uses the Affero GPL 3. This example however uses a
3-clause BSD license, because you may not want to use the GPL on your slides.
:-) Well if you do, hat off to you, but of course you don't have to.

lecture-slides.js_ (https://www.github.com/DennisSchulmeister/lecture-slides.js) <br/>
This template: (https://www.github.com/DennisSchulmeister/ls-presentation-template) <br/>
© 2017  Dennis Schulmeister-Zimolong <dennis@pingu-mail.de>
