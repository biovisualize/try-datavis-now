# Canvas

Canvas is another syntax for drawing in the browser. Difference between immediate and retained mode, vector and raster. The canvas element by itself doesn't do anything. It needs some javascript to paint it in.

```html
<!DOCTYPE html>
	<head>
		<title>Page title</title>
		<style>
		</style>
	</head>
	<body>
		<canvas></canvas>
	    <script>
		    var canvas = document.querySelector('canvas')  
		    var context = canvas.getContext('2d')
		    context.fillStyle = "#FF0000";
			context.fillRect(0, 0, 150, 75);
    	</script>
	</body>
</html>
```