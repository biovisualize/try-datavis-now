# HTML

Not a programming language: a markup language. Believe it or not, you could build websites using only HTML. It would be light and fast, easy to maintain by a designer without the need of a programmer, SEO-friendly, easy to cache, and it forces you to think of the content first. Why then all websites are so heavy and slow? 

* They use libraries and frameworks they don't need
* They have useless/annoying features (ads, sign-up pop-ups, chat panel, responsive hamburgers menu)
* They have lots of trackers (Google analytics, screen replay, Mixpanel, pixel trackers, cookies)
* They don't optimize images/videos
* They have lots of browser and resolution specific code
* They use huge blog CMS and generators

All website will anyway end-up being HTML, so it's worth learning it properly. [HTML5](http://diveintohtml5.info/)

HTML define the "structure" of the page, if a section is a title, a paragraph, a footer, a generic container, etc.

<a class="jsbin-embed" href="http://jsbin.com/dacupu/embed?html,output&height=500px"> on jsbin.com</a><script src="http://static.jsbin.com/js/embed.min.js?3.36.11"></script>

There are less than a hundred usable [tags in HTML](http://www.w3schools.com/tags/). But you can easily survive with a smaller subset:

```html
<!--...-->	Defines a comment
<a>	Defines a hyperlink
<br>	Defines a single line break
<p>	Defines a paragraph
<pre>	Defines preformatted text
<h1> to <h6>	Defines HTML headings
<iframe>	Defines an inline frame
<img>	Defines an image
<div>	Defines a section in a document
<span>	Defines a section in a document

<form>	Defines an HTML form for user input
<input>	Defines an input control
<button>	Defines a clickable button
<select>	Defines a drop-down list
<option>	Defines an option in a drop-down list
<textarea>	Defines a multiline input control (text area)

<ul>	Defines an unordered list
<li>	Defines a list item

<table>	Defines a table
<td>	Defines a cell in a table
<th>	Defines a header cell in a table
<tr>	Defines a row in a table

<canvas>	Used to draw graphics, on the fly, via scripting (usually JavaScript)

<link>	Defines the relationship between a document and an external resource (most used to link to style sheets)
<style>	Defines style information for a document
<script>	Defines a client-side script

```

HTML tags have attributes, like the "src" attribute of the "img" tag:

```html
<img src="image.png">
```

<div class="tips">
Most HTML tag also have a closing tag, like &lt;h1&gt;&lt;/h1&gt;. But some are self closing like &lt;br&gt;, &lt;hr&gt;, &lt;img&gt;, &lt;input&gt;, &lt;link&gt; and &lt;meta&gt;. 
Those are called [void elements](https://www.w3.org/TR/html5/syntax.html#void-elements) and can be written as &lt;br&gt; or &lt;br/&gt;, but not &lt;br&gt;&lt;/br&gt;.
</div>
