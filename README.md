compack
=======

A pack of fixing older browsers Compatibility.


usage
=======


2. **cssFx** is a standalone polyfill that adds all the vendor-specific CSS3 properties you normally have to add for older browsers. 

example:
```css
<link rel="stylesheet" href="effects.css" class="cssfx"> 
```
```js
<script src="cssfx.min.js"></script>
```


3. **DD_belatedPNG** a Javascript library that sandwiches PNG image support into IE6 without much fuss.

example:
```js
<!--[if IE 6]>
<script type="text/javascript" src="DD_belatedPNG_0.0.8a-min.js"></script>
<script>
DD_belatedPNG.fix('id or class, type');
</script>
<![endif]-->
```
P.S.type:img or background.


4. **html5shiv** is a HTML5 IE enabling script.

example:
```js
<!--[if lt IE 9]>
<script type="text/javascript" src="html5shiv-printshiv.js"></script>
<![endif]-->
```


5. Modernizr is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser.


6. **PIE** makes Internet Explorer 6-9 capable of rendering several of the most useful CSS3 decoration features.

example:
```css
behavior: url(path/to/pie_files/PIE.htc);
```
P.S.In that same CSS rule, add this style line.


7. **minmax** makes CSS minimum and maximum sizes.

example:
```js
<script type="text/javascript" src="minmax.js"></script>
```


8. **fixed** fix IE6 fixed positioning.

example:

add `ie6fixedTL` or `ie6fixedBR` to class.
