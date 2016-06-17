# Boilerplate to start with D3

```html
<!DOCTYPE html>
	<head>
		<meta charset="utf-8">
		<script src="https://d3js.org/d3.v3.js"></script>
		<style>
			.bar{
				background-color: orange;
				position: relative;
				float: left;
				margin-right: 10px
			}
		</style>
	</head>
	<body>
		<div class="container"></div>
		<script>

		 	var containerSelection = d3.select('.container')
		 		.style({
		 			width: '500px',
		 			height: '300px',
		 			'background-color': 'aliceblue'
		 		});

	 		containerSelection.selectAll('div.bar')
		      	.data([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
			 			.enter().append('div')
		      	.attr({
		        	class: 'bar'
		      	})
	 			.style({
	 				width: '40px',
	 				height: function(d){ return d*20; },
	        		top: function(d){ return 300 - d*20 + 'px'; },
	 			});

		</script>
	</body>
</html>
```