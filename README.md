Typeahead.js and Bootstrap 3
============================

For Bootstrap 4 try [typeaheadjs.css](https://github.com/bassjobsen/typeahead.js-bootstrap4-css/)

typeahead.js
------------
The [typeahead.js](https://github.com/twitter/typeahead.js) library consists of 2 components: the suggestion engine, Bloodhound, and the UI view, Typeahead. The suggestion engine is responsible for computing suggestions for a given query. The UI view is responsible for rendering suggestions and handling DOM interactions. Both components can be used separately, but when used together, they can provided a rich typeahead experience.

Bootstrap 3
-----------
Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development, created by [Mark Otto](http://twitter.com/mdo) and [Jacob Thornton](http://twitter.com/fat), and maintained by the [core team](https://github.com/twbs?tab=members) with the massive support and involvement of the community.

To get started, check out <http://getbootstrap.com>!

History
-------
With Twitter Bootstrap 3 the typeahead plugin had been dropped. [@mdo](http://twitter.com/mdo) says: "in favor of folks using [Twitter's typeahead](https://github.com/twitter/typeahead.js). Twitter's typeahead has more features than the old bootstrap-typeahead.js and less bugs." Twitter's typeahead don't work direct with Bootstrap 3. The DOM structure of the dropdown menu used by `typeahead.js` differs from the DOM structure of the Bootstrap dropdown menu. You'll need to load some additional CSS in order to get the `typeahead.js` dropdown menu to fit the default Bootstrap theme. You can download the basic CSS here, or use the LESS file to integrate it into your project. CSS and LESS are build with the latest LESS code of Bootstrap 3.1.0. Code does not introduce new mixins and only extends Bootstrap's LESS. If you search for a more extended version try: [typeahead.js-bootstrap3.less](https://github.com/hyspace/typeahead.js-bootstrap3.less/blob/master/typeahead.less).

Note also the [orginal typeahead plugin](https://github.com/bassjobsen/Bootstrap-3-Typeahead) still works with Bootstrap 3. 

Download
========

 - Download the latest [typeaheadjs.css](https://github.com/bassjobsen/typeahead.js-bootstrap-css/blob/master/typeaheadjs.css) or [typeaheadjs.less](https://github.com/bassjobsen/typeahead.js-bootstrap-css/blob/master/typeaheadjs.less).

How to use
==========

CSS
---
Include the CSS file after Bootstrap's CSS in your HTML:

	<link href="bootstrap-3.1.0/dist/css/bootstrap.min.css" rel="stylesheet">
	<link href="typeaheadjs.css" rel="stylesheet">

LESS
----
 1. Copy typeaheadjs.less into your Bootstrap's LESS folder
 2. Import this file into bootstrap.less: `@import "typeaheadjs.less";`
 3. Recompile Bootstrap 
 
Example
-------
![ScreenShot](https://raw.github.com/bassjobsen/typeahead.js-bootstrap-css/master/screenshot.png)
