# Javascript

Javascript is the scripting language hosted by your browser. It can automate lots of things, like manipulating the document, add/remove/modify HTML/SVG/CSS elements. 

```html
<!DOCTYPE html>
	<head>
		<meta charset="utf-8">
		<script src="lib/d3.js"></script>
		<style>
			.foo {
				font-style: italic;
			}
			.bar {
				fill: red;
				stroke: white;
			}
		</style>
	</head>
	<body>
		<div class="container">
			<h1>Title</h1>
			<p>Paragraph</p>
			<p>Paragraph with text in <span class="foo">italic</span></p>
			<svg height="297mm" width="210mm">
 				<rect height="60" width="50" stroke="#000" y="6" x="7" fill="#f00"/>
 				<rect class="bar" height="60" width="50" y="6" x="7" />
			</svg>
		</div>
		<script>

		 document.querySelector('.bar').style.fill = 'skyblue';

		</script>
	</body>
</html>
```