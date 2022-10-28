---
layout: ~/layouts/Markdown.astro
---

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

<h2>Fluid Font Sizes</h2>

**--fluid-0**
<p style="font-size:var(--fluid-0);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>   

**--fluid-1**
<p style="font-size:var(--fluid-1);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>

**--fluid-2**
<p style="font-size:var(--fluid-2);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>

**--fluid-3**
<p style="font-size:var(--fluid-3);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>

**--fluid-4**
<p style="font-size:var(--fluid-4);">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?</p>

**Typography**:

Lorem, ipsum dolor sit amet consectetur [adipisicing elit](https://www.google.com). `Voluptatum nostrum dicta asperiores` hic porro ~~consequatur illum dolorem~~ suscipit dolores mollitia! **Voluptate, atque?** *Doloribus natus odit eius nihil tempore, sequi dignissimos*.

[Example Link](https://www.google.com "Google's Homepage")

[`Example Link`](https://www.google.com "Google's Homepage")

* Unordered list can use asterisks
- Or minuses
+ Or pluses

1. First ordered list item
2. Another item
   * Unordered sub-list. 
3. Actual numbers don't matter, just that it's a number
   1. Ordered sub-list
4. And another item.

**Footnotes**:

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

**Blockquotes**:

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

**Code Blocks**:

single: 

`Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repudiandae, neque ratione. Repudiandae, laboriosam porro. Omnis, autem voluptatum? Dolores ipsa earum nisi eaque? Quis dolores quos illo necessitatibus illum perspiciatis ea?`

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
```

**Tables**:

<table role="grid">
<thead>
   <tr>
      <th scope="col">#</th>
      <th scope="col">Heading</th>
      <th scope="col">Heading</th>
      <th scope="col">Heading</th>
      <th scope="col">Heading</th>
      <th scope="col">Heading</th>
      <th scope="col">Heading</th>
      <th scope="col">Heading</th>
   </tr>
</thead>
<tbody>
   <tr>
      <th scope="row">1</th>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
   </tr>
   <tr>
      <th scope="row">2</th>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
   </tr>
   <tr>
      <th scope="row">3</th>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
   </tr>
</tbody>
</table>

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

**Images**:

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

**Page Breaks**:

---

Hyphens

***

Asterisks

___

Underscores


