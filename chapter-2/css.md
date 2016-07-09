# CSS

[CSS](http://reference.sitepoint.com/css) is very useful to separate the semantic from the style.

We could say that CSS takes care of two things: the graphical style and the geometry. 

Graphical style:
* font, text style
* colors, borders, patterns

Geometry
* position
* sizes
* padding and margins

<a class="jsbin-embed" href="http://jsbin.com/dacupu/embed?html,output&height=500px"> on jsbin.com</a><script src="http://static.jsbin.com/js/embed.min.js?3.36.11"></script>

```html
<!DOCTYPE html>
	<head>
		<title>Page title</title>
		<style>
			.foo {
				font-style: italic;
			}
		</style>
	</head>
	<body>
		<div class="container">
			<h1>Title</h1>
			<p>Paragraph</p>
			<p>Paragraph with text in <span class="foo">italic</span></p>
		</div>
	</body>
</html>
```

There are 3 ways to apply a style
```html
<!DOCTYPE html>
	<head>
		<title>Page title</title>
		<!-- external file -->
		<link rel="stylesheet" href="style/style.css">
		<!-- in the header -->
		<style>
			.foo {
				font-style: italic;
			}
		</style>
	</head>
	<body>
		<!-- inline using the style attribute -->
		<div class="foo" style="color:red">Some text</div>
	</body>
</html>
```

<div class="tips">
The "cascading" is CSS means if you have multiple styles applied to the same element and conflicting, for example trying to set the color of the same font, the style that will be applied is the one closer to the tag. So the inline style will have a priority over non-inline, then it depends on the position in the stylesheet. 

Some attributes have the same function as some styles. For example, what color will the following rectangle be?
</div>

```html
<!DOCTYPE html>
	<head>
		<title>Page title</title>
		<style>
			rect {
				fill: blue;
			}
		</style>
	</head>
	<body>
		<svg><rect x="10" y="10" width="100" height="100" fill="green" style="fill:red"/></svg>
	</body>
</html>
```

Red
<svg><rect x="10" y="10" width="100" height="100" fill="green" style="fill:red"/></svg>

<div class="tips">
I suggest to use styles whenever you have the choice. It will make it easier to extract them to an external stylesheet for example. Keep in mind that a style like <pre>width:100px</pre> needs a unit like "px", where an attribute like <pre>width="100"</pre> will take a default one if not specified.
</div>

CSS uses selectors to know on which tag to apply the style. Simple selectors can be a tag name, an id or or a class. 
```html
<!DOCTYPE html>
	<head>
		<title>Page title</title>
		<style>
			<!-- tag name -->
			div {
				color: blue;
			}
			<!-- id -->
			#foo {
				color: green;
			}
			<!-- class -->
			.bar {
				color: red;
			}
		</style>
	</head>
	<body>
		<div>A</div>
		<div id="foo">B</div>
		<div class="bar">C</div>
	</body>
</html>
```

<div class="tips">
There's a convention that there should never be two elements with the same id. A class should be used instead to apply style to multiple elements. But nothing will break if you don't respect this convention. You can also have multiple classes to identify the same element like <pre>&lt;div class=&quot;foo bar&quot;&lt;/div&gt;</pre>
</div>