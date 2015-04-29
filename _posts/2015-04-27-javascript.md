---
layout: post
title: Need-to-Know Code 
---

Here are a few aspects of HTML, CSS, JavaScript, SVG and general code-jargon that may be of assistance, even if it's just helping with terms and concepts to Google.

#### General Tips

* Try to find a text editor that you like that supports code highlighting, it can make spotting issues much easier.
* Be aware that markup languages do not handle special characters,< >, apostrophes, or quotation marks elegantly. They generally need some help and that help is often in a [Character Entity Reference](http://dev.w3.org/html5/html-author/charref) which you use in your text instead of the problem-character. (`&name;` version should be sufficient in most cases)
* Be aware that like most programming languages there are 'reserved words' which can't be used for variable names, for example `type`.
 
#### HTML

* Basic structure `<p id="demo" style="text-align:center;color:red">Inner text.</p>`.
* American spelling (i.e. center, color).
* ids are used if you want to refer to a particular element.
* Use names if you are wanting to submit data via form.
* Elements can have both ids and names.
* Class or style attributes make HTML elements pretty. 
* Classes can also be used to make things selectable in D3.
* Most D3 visualisations use `<div>` tags to 'place' the D3 elements on the page although function wise, they are quite limited.

#### CSS

* Can be included in the `<head>` element, as a linked style sheet or inline as an attribute.
* Sytax changes slightly depending on which one of these you're using.
* Also uses American spelling (i.e. center, color).
* CSS Type Selectors are very important and it's worth trying to figure these out as they are quite powerful.

#### JavaScript

* Selectors:

<table>
<thead>
<th>Selector</th><th>Selects</th>
</thead>
<tbody>
<tr>
  <td>$("#bob")</td>
  <td>The element with id="bob"</td>
</tr>
<tr>
  <td>$(".pink")</td>
  <td>All elements with class="pink"</td>
</tr>
<tr>
  <td>$(".pink,.blue")</td>
  <td>All elements with class="pink" or class="blue"</td>
</tr>
<tr>
  <td>$("div")</td>
  <td>All < div > elements"</td>
</tr>
<tr>
  <td>$("div,p,svg")</td>
  <td>All &lt;div&gt;, &lt;p&gt; and &lt;svg&gt; elements</td>
</tr>
</tbody>
</table>


#### SVG

* Use `text-anchor: middle` to centre text in an SVG text element (`start` and `end` are the other options).

#### General Terms & Concepts

* A "cast" or "casting" is what you're doing when you want to turn a variable into another type of variable. Common casts include turning strings into numbers and back again. JavaScript gives you a few options to do this, and most data type conversions follow this pattern: `Number("3.14")` or `(3.14).toString() or x.toString()`.
