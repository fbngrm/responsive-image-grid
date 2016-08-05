# image-grid

**image-grid** is a mobile friendly responsive grid optimized for three different image formats. It is build with a subset of the awesome [spectre.css](https://github.com/picturepan2/spectre) and uses its [responsive grid](http://picturepan2.github.io/spectre/#responsive) customized to work well with image ratios of **2/3**, **3/4** and **1/1**.  

# Demo

* [analog-format 2/3](https://fgrimme.github.io/demo/analog.html)
* [digital-format 3/4](https://fgrimme.github.io/demo/digital.html)
* [square-format 1/1](https://fgrimme.github.io/demo/square.html)

# Installation

**Install manually**

Download the compiled and minified [CSS file](https://github.com/fgrimme/image-grid/blob/master/dist/image-grid.min.css)

**Install wit NPM**

`$ npm install responsive-image-grid`

And include it in your site.

`<link rel="stylesheet" href="dist/image-grid.min.css" />`

# Usage

Images should have the correct ratio in landscape or portrait orientation. Have a look at the files in the [demo](https://github.com/fgrimme/image-grid/blob/master/demo/) directory to see how to use the grids. To adjust the padding change the `@image-gutter` variable in [variables.less](https://github.com/fgrimme/image-grid/blob/master/src/variables.less). Then compile the css with `gulp build`.


# License
[MIT](https://github.com/fgrimme/image-grid/blob/master/LICENSE)
