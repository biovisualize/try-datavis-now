# HTML

Not a programming language: a markup language. Believe it or not, you could build websites using only HTML. It would be light and fast, easy to maintain by a designer without the need of a programmer, SEO-friendly, easy to cache, and it forces you to think of the content first. Why then all websites are so heavy and slow? 

* They use libraries and frameworks they don't need
* They have useless/annoying features (ads, sign-up pop-ups, chat panel, responsive hamburgers menu)
* They have lots of trackers (Google analytics, screen replay, Mixpanel, pixel trackers, cookies)
* They don't optimize images/videos
* They have lots of browser and resolution specific code
* They use huge blog CMS and generators

All website will anyway end-up being HTML, so it's worth learning it properly. [HTML5](http://diveintohtml5.info/)

HTML define the semantic of the page, if a section is a title, a paragraph, a footer, a generic container, etc.

```html
<!DOCTYPE html>
	<head>
		<title>Page title</title>
		<style>

		</style>
	</head>
	<body>
		<div class="container">
			<h1>Title</h1>
			<p>Paragraph</p>
			<p>Paragraph with text in <i>italic</i></p>
		</div>
	</body>
</html>
```