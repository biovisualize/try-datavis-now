# Javascript

Javascript is the scripting language hosted by your browser. It can automate lots of things, like manipulating the document, add/remove/modify HTML/SVG/CSS elements. 

<a class="jsbin-embed" href="http://jsbin.com/dacupu/embed?html,output&height=500px"> on jsbin.com</a><script src="http://static.jsbin.com/js/embed.min.js?3.36.11"></script>

```html
<!DOCTYPE html>
	<head>
	</head>
	<body>
		<svg height="297mm" width="210mm">
			<rect class="bar" height="60" width="50" y="6" x="7" />
		</svg>
		<script>

		 document.querySelector('.bar').style.fill = 'skyblue';

		</script>
	</body>
</html>
```

A good way to learn Javascript is with the [Codecademy](https://www.codecademy.com/learn/javascript) class or the [Mozilla Javascript guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide).

This is the bare minimum to survive in Javascript world:

```html
<script>

// this is a comment

// this is a variable named "foo" containing the value 1
var foo = 1;

// this is an array named "bar" containing a series of numbers
var bar = [1, 2, 3, 4];

// this is an object named "baz" containing a serie of key:value pairs
var baz = {a: 1, b: 2};

// you can access every value by key
var bazA = baz.a;
// or the equivalent
var bazA = baz['a'];

// this is a function named "aaa" expecting an argument 
// and returning the value of this argument + 1
function aaa(d){
	return d + 1;
}

// this is an example of how you use it
var result = aaa(2);

// and you can all use them together
var something = [{a: function(d){ return d + 'px'; }}, 10, baz.a, aaa(10)];

</script>
</html>
```

All of these variables, functions, arrays, strings, numbers, etc. are [objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects). They all have an associated [object tree](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects) that looks like the DOM (in fact, there are also some [primitives](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String#Distinction_between_string_primitives_and_String_objects) that are wrapped into objects). You can look at their structure same as the DOM using the Developer tools console. 