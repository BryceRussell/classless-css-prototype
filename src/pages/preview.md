---
layout: ~/layouts/Base.astro
---

<h1>This is Big a Test Heading</h1>
<h2>h2 Heading</h2>
<h3>h3 Heading</h3>
<h4>h4 Heading</h4>
<h5>h5 Heading</h5>
<h6>h6 Heading</h6>
<strong>Default Text:</strong>
<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatum nostrum dicta asperiores hic porro consequatur illum dolorem suscipit dolores mollitia! Voluptate, atque? Doloribus natus odit eius nihil tempore, sequi dignissimos.</p>
<hr>
<h2>Fluid Font Sizes</h2>
<strong>--fluid-0</strong>
<p style="font-size:var(--fluid-0);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>   
<strong>--fluid-1</strong>
<p style="font-size:var(--fluid-1);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>
<strong>--fluid-2</strong>
<p style="font-size:var(--fluid-2);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>
<strong>--fluid-3</strong>
<p style="font-size:var(--fluid-3);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>
<strong>--fluid-4</strong>
<p style="font-size:var(--fluid-4);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>
<strong>--fluid-5</strong>
<p style="font-size:var(--fluid-5);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

Three or more...

---

Hyphens

***

Asterisks

___

Underscores

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

