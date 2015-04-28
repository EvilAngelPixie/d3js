---
layout: post
title: Need-to-Know Code 
---

Here are a few aspects of HTML, CSS, JavaScript, SVG and general code-jargon that may be of assistance, even if it's just helping with terms and concepts to Google.

#### General Tips

* Try to find a text editor that you like that supports code highlighting, it can make spotting issues much easier.
* Be aware that markup languages do not handle special characters,< >, appostropies, or quotation marks elegantly. They generally need some help and that help is often in a Character Entity Reference. 
 

#### HTML

* Basic structure `<p id="demo" style="text-align:center;color:red">Inner text.</p>`.
* American spelling (i.e. center, color).
* ids are used if you want to refer to a particular element.
* Use names if you are wanting to submit data via form.
* Class or style attributes make HTML elements pretty. 
* Classes can also be used to make things selectable in D3.
* Most D3 visualisations use `<div>` tags to 'place' the D3 elements on the page although function wise, they are quite limited.

#### CSS

* Can be included in the `<head>` element, as a linked style sheet or inline as a attribute.
* Sytax changes slightly depending on which one of these you're using.
* Also uses American spelling (i.e. center, color).
* CSS Type Selectors are very important and it's worth trying to figure these out as they are quite powerful.

#### JavaScript


#### SVG
* Use `text-anchor: middle` to centre text in an SVG text element (`start` and `end` are the other options).

#### General Terms & Concepts

* A "cast" or "casting" is what you're doing when you want to turn a variable into another type of variable. Common casts include turning strings into numbers and back again. JavaScript gives you a few options to do this, and most data type conversions follow this pattern: `Number("3.14")` or `(3.14).toString() or x.toString()`.
