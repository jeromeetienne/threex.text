threex.text
===========

threex.text is a [threex game extension for three.js](http://jeromeetienne.github.io/threex/) which makes it easy to add 3d text in your game. You can use it to create a big logo on top of a shop or a big sign of any kind Las Vegas style. Up to you to see :) It is very flexible. You can fine tune lots of parameters to make it fit your needs. You can choose the fonts, the size, the bevel, the weight etc...


Show Don't Tell
===============
* [examples/basic.html](http://jeromeetienne.github.io/threex.text/examples/basic.html)
\[[view source](https://github.com/jeromeetienne/threex.text/blob/master/examples/basic.html)\] :
It shows a 3d text.
* [examples/requirejs.html](http://jeromeetienne.github.io/threex.text/examples/requirejs.html)
\[[view source](https://github.com/jeromeetienne/threex.text/blob/master/examples/requirejs.html)\] :
It show a 3d text and it is all loaded thru require.js


A Screenshot
============
[![screenshot](https://raw.githubusercontent.com/jeromeetienne/threex.text/master/examples/images/screenshot-threex-text-512x512.jpg)](http://jeromeetienne.github.io/threex.text/examples/basic.html)

How To Install It
=================

You can install it via script tag

```html
<script src='threex.text.js'></script>
```

Or you can install with [bower](http://bower.io/), as you wish.

```bash
bower install threex.text
```

How To Use It
=============

Here is a very basic usage

```
var mesh	= new THREEx.Text('THREEx')
scene.add(mesh)
```

Here is another example with more parameters. The options are passed directly 
to  ```THREE.TextGeometry```. 
See [three.js docs](http://threejs.org/docs/#Reference/Extras.Geometries/TextGeometry)
for details.

```
var mesh	= new THREEx.Text('THREEx', {
	font		: "droid serif",
	weight		: "bold",
	size		: 1,
	height		: 0.4,
})
scene.add(mesh)
```