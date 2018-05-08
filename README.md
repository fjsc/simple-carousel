# \<simple-carousel\>
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/franjsc/simple-carousel)
  
[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/fjscsimple-carousel)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/fjscsimple-carousel.svg)](https://vaadin.com/directory/component/fjscsimple-carousel)


`<simple-carousel>` is a simple configurable carousel component for Polymer 1.0. It provides a simple way to insert HTML content in slides and multiple options to configure their functionality and transitions.

For example, the following code implements the most simple configuration for the carousel:

```html
<simple-carousel>
	<carousel-slide>
	  <h3>1</h3>
	</carousel-slide>
	<carousel-slide>
	  <h3>2</h3>
	</carousel-slide>
	<carousel-slide>
	  <h3>3</h3>
	</carousel-slide>         
</simple-carousel>
```

You can also use attributes (with or without the `data-` prefix):

```html
<simple-carousel>
  <div carousel-slide>
    <h3>1</h3>
  </div>
  <div carousel-slide>
    <h3>2</h3>
  </div>
  <div data-carousel-slide>
    <h3>3</h3>
  </div>         
</simple-carousel>
```

## Demo


> [Demo 1](https://fjsc.github.io/simple-carousel/components/simple-carousel/)

<img src="http://www.bugui.org/Images/carousel.png" width="340"/>

## Install

Install with [Bower](http://bower.io):

```sh
$ bower install --save polymer-simple-carousel
```


## Usage

1. Import Custom Element:

```html
<link rel="import" href="simple-carousel.html">
```

## API Reference

> [API Reference](https://franjsc.github.io/simple-carousel/components/simple-carousel/)


## License

Apache License 2.0
