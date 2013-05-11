compack
=======

A pack of multi explorer support


usage
=======


1.cssFx is a standalone polyfill that adds all the vendor-specific CSS3 properties you normally have to add for older browsers. 
example:

```css
<link rel="stylesheet" href="effects.css" class="cssfx"> 
```
```js
<script src="cssfx.min.js"></script>
```


2.DD_belatedPNG a Javascript library that sandwiches PNG image support into IE6 without much fuss.
example:

<!–[if IE 6]>

```js
<script type=”text/javascript” src=”DD_belatedPNG_0.0.8a-min.js”></script>
<script>
DD_belatedPNG.fix('id or class, type');
</script>
```

<![endif]–>

P.S.type:img or background.


3.html5shiv is a HTML5 IE enabling script.
example:

<!--[if lt IE 9]>
```js
<script type="text/javascript" src="html5shiv-printshiv.js"></script>
```
<![endif]-->



4.Modernizr is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser.

5.PIE makes Internet Explorer 6-9 capable of rendering several of the most useful CSS3 decoration features.
example:

```css
behavior: url(path/to/pie_files/PIE.htc);
```

P.S.In that same CSS rule, add this style line.


6.minmax makes CSS minimum and maximum sizes.
example:

```js
<script type="text/javascript" src="minmax.js"></script>
```
