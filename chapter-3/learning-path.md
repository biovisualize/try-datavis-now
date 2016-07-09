# Learning path

<a class="jsbin-embed" href="http://jsbin.com/qojugi/embed?html,output&height=500px"> on jsbin.com</a><script src="http://static.jsbin.com/js/embed.min.js?3.36.11"></script>

## d3.selection
```javascript
d3.select('.first').style('color', 'red');
d3.select('.first').attr('id', 'foo');
```

```javascript
d3.selectAll('div').style('color', 'red');
```

```javascript
d3.select('.first').text('The First Box!');
d3.select('.first').html('<h1>The First Box!</h1>');
```

```javascript
d3.select('.first').append('h2').text('title');
```

```javascript
d3.select('.first').select('h2').remove();
d3.select('.first h2').remove();
```

```javascript
var data = [1, 2, 3, 4];

data.forEach(function(d){
	d3.select('.first').append('p').text('paragraph ' + d);
});
```

```javascript
var data = [1, 2, 3, 4];

d3.select('.first').selectAll('p')
	.data(data)
	.enter()
	.append('p')
	.text('paragraph ' + d);
```

