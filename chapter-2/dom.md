# DOM

Under the hood, all these technologies can be accessed using their common internal representation called the DOM (Document Object Model).

> A Web page is a document. This document can be either displayed in the browser window, or as the HTML source. But it is the same document in both cases. The Document Object Model (DOM) provides another way to represent, store and manipulate that same document. The DOM is a fully object-oriented representation of the web page, and it can be modified with a scripting language such as JavaScript.

From https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction

One way to demystify the DOM is to use Chrome Developer Tools. Let's jump on Scott's Murray book to learn more about it http://chimera.labs.oreilly.com/books/1230000000345/ch03.html#developer_tools_3.

The DOM provides lots of methods to navigate the tree, manipulate attributes, content, styles, etc. The best book to learn how to master the DOM is [DOM Enlightenment](http://shop.oreilly.com/product/0636920027690.do). Let's just look at how to select an element using a DOM method from Javascript and a simple selector like we used for css:

```html
<script>
// using a DOM method
document.querySelector('.foo');
</script>

```

If you used jQuery or D3 before, this method looks a lot like:
```html
<script>
// using jQuery
$('.foo');

// using D3
d3.select('.foo');
</script>

```
The difference is that jQuery will return a DOM node wrapped as a jQuery object and D3 as a d3.selection. In both case, you can get access to the raw DOM node from these wrapped selections. But both libraries are providing a lot of goodies over what the DOM methods provide.