## D3 design philosophy
D3 is really just a **thin layer** to help you use web technologies. There's no magic in D3. We often see the question: "can I do this with D3?" The answer usually is: if you can do it with web technologies, D3 will just help you do it more efficiently. 

D3 has a reputation of being difficult to learn. It's only partly true. First, it uses some **[functional patterns](http://eloquentjavascript.net/1st_edition/chapter6.html)**, not really the hardcore functional stuff, but still more difficult to learn when you come from an object-oriented mindset for example. But Javascript is pretty powerful as a functional language so it totally worth learning it. A good place to start is with [this book](http://shop.oreilly.com/product/0636920028857.do).

Second, D3 is a set of tools, so you need to know how to use them together. You can find plenty of **[examples](https://bost.ocks.org/mike/example/)** and [documentation](https://github.com/d3/d3/wiki/API-Reference), but there are so many combinations and use cases that they can't all be covered. And the examples doesn't help much when you need to get to the next level, like packaging charts, pipe in your own data, integrate them into an app, etc.

Third, people often start with D3 before **learning the basics**. So a lot of questions are answered by referring people to the main CSS, HTML, Javascript and especially DOM documentations.

Fourth, D3 is often confused with abstraction libraries like jQuery or Raphael.js. But it's **not an abstraction**. It's also not a framework. In fact, it's often described by a lots of things it is not. 

Also, my personal opinion is that even though the enter-update-exit pattern and the whole data-binding pattern is a fundamental piece of D3, it may not be the best place to start. That contradicts most of the tutorials and books you can see out there. But let's try it and see where an **alternative learning path** would lead.

<a href="http://vis.stanford.edu/files/2011-D3-InfoVis.pdf">D3.js paper</a><br />