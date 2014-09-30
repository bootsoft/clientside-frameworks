= Responsive Frameworks=

Responsive frameworks provide the following :

* A responsive grid to support a mobile first approach to design and development
* A considered, and consistent base set of styles for typography
* A UI kit of styles for buttons, forms, lists, and other common elements
* A Set of of JS widgets, usually in the form of jQuery plugins for some added functionality

Responsive frameworks often are large and bloated, this is because they take a one size fits all philosophy, if client side rendering performance - particularly in mobile - is of major concern, consider rolling your own grid, or using one of the lighter frameworks.

== Twitter Bootstrap ==

Twitter Bootstrap is the most widely used responsive framework.  It supports both SASS and LESS for css preprocessing.  The latest version 3 does not support IE8 out of the box. This framework is very large.  http://getbootstrap.com/

== Zurb Foundation ==

Zurb Foundation is a responsive framework similar to Twitter Bootstrap, the main differences are that Foundation is built purely mobile first and uses REM units for relative font sizing.  For IE8 support, use version 3.2. This framework is very large.  http://foundation.zurb.com/index.html

== Bourbon Neat ==

Bourbon Neat is a semantic responsive grid built on SASS.  It does not have opinions bout typography or element style.  http://neat.bourbon.io/

= Javascript MVC =

== Backbone ==

BackboneJS is a lightweight MVC that can be used on the front end or in Node.  It has simple classes for models, collections, and views.  The collections are extended with functional components for UnderscoreJS.  It also has a router that supports HTML5 push state.  Backbone is an excellent choice for many types of projects.  It is not opinionated, though there extensions that help to create convention and structure. http://backbonejs.org/

== AngularJS ==

AngularJS is a very opinionated framework supported by Google.  It excels in handling data binding and abstracts lots of boilerplate code.  Angular is in control of the render, and does not easily allow for other templating solutions other than the built in templates.  It is powerful framework and is built to enhance unit testing, as well as error reporting. https://angularjs.org/

= Libraries =

== UnderscoreJS ==

Underscore is a functional toolset for javascript.  It provides many methods for iterating on, and manipulating JS objects and/or arrays.  Underscore is lightweight and extremely useful.  It is highly recommended that Underscore be part of any project.  http://underscorejs.org/

== LoDash ==

LoDash is almost an identical clone of Underscore, though it boasts more performance and more methods.  http://lodash.com/

== jQuery ==

jQuery is a library that has very robust toolset and works to manipulate the DOM, and handle Ajax for the developer.  jQuery is very large, and non-performant on mobile devices.  http://jquery.com/
