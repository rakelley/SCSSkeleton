# SCSSkeleton - DEPRECATED

`SCSSkeleton` was a SCSS rewrite of the 1.0 version of the Skeleton fluid grid CSS framework - www.getskeleton.com

Some time ago, version 2.0 of Skeleton was released, an excellent major rewrite that was significantly streamlined and renders this project unnecessary in my opinion.  It is now considered deprecated.


## Features

In addition to all the wonderful features native to Skeleton, `SCSSkeleton` offers:

### Mixin-based Grids with Control Variables

`SCSSkeleton` uses variables to control all aspects of the grid and the width breakpoints, and mixins to write the actual grid code, allowing you to quickly modify the existing four grid rulesets or add your own.  Make changes once and significantly reduce the amount of math required.

### Shorthand Media Queries

`SCSSkeleton` provides mixins for all media queries, allowing you to use, for instance, `@include media-base {` instead of writing out `@media screen and (min-width: 960px) {` each time.  More importantly, all media queries of a given type will automatically reflect changes you make.

### Integrated Compass Mixins

`SCSSkeleton` uses the excellent css3 mixins built into Compass to fill in vendor prefixes for css3 attributes, providing single-point-of-change and making sure your syntax is up to date.

### Complete Skeleton Equivalency

`SCSSkeleton` compiles equivalently to Skeleton so no rewriting of your site styles is required if you're using the original stylesheets.  The only addition to the code base is an optional "Wide" grid which is commented out by default.  `SCSSkeleton` simply saves time and allows you to more easily make your own changes to Skeleton, it does not alter the function of the framework on its own.


## Dependencies

* Ruby http://www.ruby-lang.org/en/downloads/
* Compass http://compass-style.org/
* SASS 3.2.0 or later http://sass-lang.com/
