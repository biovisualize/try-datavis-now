# SVG

Markup for graphics.

```html
<!DOCTYPE html>
	<head>
		<title>Page title</title>
		<style>
			.bar {
				fill: red;
				stroke: white;
			}
		</style>
	</head>
	<body>
		<svg height="300" width="500">
				<rect height="60" width="50" stroke="#000" y="6" x="7" fill="#f00"/>
				<rect class="bar" height="60" width="50" y="6" x="7" />
		</svg>
	</body>
</html>
```