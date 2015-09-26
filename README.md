# Galarie.css

Galarie.css is all *CSS* simple, lightweight carousal library. Think: Simple, maintainable photo galleries without the use of Javascript. 

_Why?_ — Galarie CSS started as an experiment, to provie a way for my photographer friends to easily build lightweight carousals without the need for jQuery, or a jQuery carousel script. It has been inspired by [Gallery CSS](http://benschwarz.github.io/gallery-css) by Ben Schwarz.

## Installation

The recommended method to install galarie-css is by using Bower.

`bower install galarie-css`

Otherwise, if you want to keep it simple, check the [dist directory](/dist).

## Getting started

You have the following types of gallery you can build using galarie.css:

	* Without autoplaying animation
	* With autoplaying animation

Read the [Getting Started Guide](http://upamanyu.in/galarie-css/#getting-started), or checkout the [examples](/examples)

## Browser support

<table width="100%" style="text-align: center;">
  <thead>
    <tr>
      <td>Safari</td>
      <td>Firefox</td>
      <td>Chrome</td>
      <td>IE8</td>
      <td>IE9</td>
      <td>IE10/11</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>✔</td>
      <td>✔</td>
      <td>✔</td>
      <td>✖†</td>
      <td>✔</td>
      <td>✔</td>
    </tr>
  </tbody>
</table>

† [Absolutely possible](examples/ie-8) using a variety of JS selector shims, although not recommended.

## Build instructions

Galarie CSS is built using [grunt](http://gruntjs.com) & RubySASS.

You'll need:

* Ruby (and sass - `gem install sass`)
* Run `npm install` from the root directory.
* To run a build, you'll simply need to run `grunt`.
