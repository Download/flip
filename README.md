# jQuery Flip <sub><sup>v1.0.11</sup></sub>

[![Greenkeeper badge](https://badges.greenkeeper.io/Download/flip.svg)](https://greenkeeper.io/)

**A lightweight jQuery plugin to create 3d flip animation.** 
See the [project page](http://nnattawat.github.io/flip/)

> This project was forked from [nnattawat/flip](https://github.com/nnatawat/flip) and has since
> been merged back into that project. Please use the original project.
	

## What's new
* **Flip v1.0.11**
  * [Added a callback that fires when flip animation is finished](https://github.com/Download/flip/commit/61b57a3d6c9a8f0dd116ca5b4444cb5356374702)

* **Flip v1.0.10**
  * [Removed log statement](https://github.com/Download/flip/commit/60a0df340b17036978a9b26b23be71204755c928)
  * [Updated license and credits](https://github.com/Download/flip/commit/9b8d218506f6b279d04a52642a8ca2fd9455d9b4)
  * [Fixed indentation](https://github.com/Download/flip/commit/acc64f52e176e7fdb5124b797b4d28cdc5bedf95)

* **Flip v1.0.9**
  * [Added support for custom front/back face selectors #27](https://github.com/nnattawat/flip/issues/27)

* **Flip v1.0.8**
  * [Added support for the mobile `tap` event](https://github.com/nnattawat/flip/issues/26)
  * [Dynamic sized content by default while maintaining backward compatibility](https://github.com/Download/flip/commit/8a6d1b3626a3c1e0e5d71fb4786c44244bf33eac)
  * Now available with [source map](http://www.html5rocks.com/en/tutorials/developertools/sourcemaps/) for better debugging support.

* **Flip v1.0.7**
  * [Improved backward compatibility](https://github.com/Download/flip/commit/b27588b1e5340ec2a6bfc5afca80a6e52b6f833f)

* **Flip v1.0.6**
  This version adds new features and fixes some issues compared to the original flip:
  * [Added support for flippable content with dynamic height/width #17](https://github.com/nnattawat/flip/issues/17)
  * [Added ability to change axis arbitrarily #1](https://github.com/download/flip/pull/1)
  * [Flip prevents bubbling of click on 'button, a, input[type="submit"], breaking e.g. Swipebox #14](https://github.com/nnattawat/flip/issues/14)
  * [Flickering animations of elements in flipped content. #16](https://github.com/nnattawat/flip/issues/16)
 
* **Flip v1.0.2 - v1.0.5**
  Chaotic period of development culminating in v1.0.6 see above.

## Getting Started

### CDN
    https://cdn.rawgit.com/nnattawat/flip/v1.0.11/dist/jquery.flip.min.js

### Download 
* [jquery.flip.js][max] (development version, commented ~9kB)
* [jquery.flip.min.js][min] (production version, minified ~4kB, gzipped ~2kB)
* [jquery.flip.min.js.map][map] (source map, ~5kB)
[max]: https://cdn.rawgit.com/nnattawat/flip/v1.0.11/dist/jquery.flip.js
[min]: https://cdn.rawgit.com/nnattawat/flip/v1.0.11/dist/jquery.flip.min.js
[map]: https://cdn.rawgit.com/nnattawat/flip/v1.0.11/dist/jquery.flip.min.js.map

### Bower
<pre>bower install flip</pre>

### Usage
In your web page:

```html

<div id="card"> 
  <div class="front"> 
    Front content
  </div> 
  <div class="back">
    Back content
  </div> 
</div>

<script src="jquery.js"></script>
<script src="jquery.flip.js"></script>
<script>
$(function($) {
  $("#card").flip(); 
});
</script>
```

## Documentation and Example

Please refer to [the project website](http://nnattawat.github.io/flip/)

## Development
Ensure that you have the latest [Node.js](http://nodejs.org/) and [npm](http://npmjs.org/) installed.

Test that Grunt's CLI and Bower are installed by running `grunt --version` and `bower --version`.  If the commands aren't found, run `npm install -g grunt-cli bower`.  For more information about installing the tools, see the [getting started with Grunt guide](http://gruntjs.com/getting-started) or [bower.io](http://bower.io/) respectively.

To run the demo locally, do the following.
<pre>
npm install
bower install
</pre>

And run grunt command to create files in /dist folder.
<pre>grunt</pre>
