# bulma-slider
 Improvement to the slider associated with CSS library Bulma

 Features:

 * Should support all major browsers but tested on Edge, Chrome, Firefox and Safari
 * Works with or without an output area
 * Supports default styling: .is-primary, .is-link, .is-info, .is-warning, .is-danger, .is-white, .is-black, .is-light, .is-dark
 * Supports .is-fullwidth

Run index.html to see three examples.

To install:

* Include bulma-slider.css in your project
* Reference it in <head> of your .html document: `<link rel="stylesheet" href="path/to/bulma-slider.css" type="text/css" media="screen" />`
* Write code:

```
<input id="slider0" class="slider is-fullwidth is-primary" min="0" max="100" value="50" step="1" type="range">
```
```
<input id="slider1" class="slider has-output is-fullwidth is-info" min="0" max="100" value="50" step="1" type="range" onchange="document.getElementById('output1').value = this.value">
<output id= "output1" for="slider1">50</output>
```
```
<input id="slider2" class="slider is-danger" min="0" max="100" value="50" step="1" type="range">
```