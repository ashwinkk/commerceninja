&lt;awesome-slider/&gt;
=================

The awesome-slider Vanilla JS custom element web component is a cool option to quickly add a slider/banner/gallery to your web projects.

## Live demo

[Access the live demo here.](https://caferati.me/demo/awesome-slider)

![awesome slider](http://i.imgur.com/j6JlUur.png)

## Browser support

![browser support](http://i.imgur.com/4bMmB5x.png)

### Quick usage

![demo](http://i.imgur.com/KKN2hVG.gif)

1. Load the WebComponents polyfill:

	```html
	<script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/0.7.5/webcomponents.min.js"></script>
	```
2. Import the custom element:

	```html
	<link rel="import" href="/awesome-slider.html">
	```
3. Use it:

	```html
	<awesome-slider pre-image="/images/logo.svg" autostart="true" bullets="true">
		<item source="/images/image-1.jpg"></item>
		<item source="/images/image-2.jpg"></item>
		<item source="/images/image-3.jpg"></item>
	</awesome-slider>
	```

## Install or download

Install the component using [Bower](http://bower.io/):

```sh
$ bower install awesome-slider --save
```
Or [download the zip file](https://github.com/rcaferati/awesome-slider/archive/master.zip).

## Troubleshooting

Join the discussion at the [article page](https://caferati.me/labs/awesome-slider)

License
-------
MIT: http://mit-license.org/

Copyright 2015 [Rafael Caferati](https://caferati.me)
