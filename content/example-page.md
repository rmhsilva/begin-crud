---
title: "Example Page"
date: 2021-02-09T08:32:58.126000

---

Things marked (WIP) are not live on [ivywrite.io](https://ivywrite.io) yet.

You can use tags to publish (as above), or <span class="roam-page">[Capture Attributes](capture-attributes)</span> instead.

<span class="roam-page">[IvyWrite](ivywrite)</span> can use either, though using attributes gives you a little more power because you can use the attribute's value in the output.

## Roam headings work as expected 

They're converted into the expected markdown heading level.

A bulleted list:

* with a **bold bit**, and a <span class="roam-tag">[#hashtag](hashtag)</span> and a page hashtag: <span class="roam-tag">[#An example attr page](an-example-attr-page)</span> 
* and a linked page February 8th, 2021
* with a nested bullet list

    - point 1 <span class="roam-highlighted">is highlighted</span> in roam and <span class="roam-highlighted">so is this bit</span>
    - point 2 _is italic_ in roam

A block ref: <span class="roam-blockref">Things marked (WIP) are not live on [ivywrite.io](https://ivywrite.io) yet.</span>

# Indent-style heading

AKA [Markus](https://dacapo.io) style headings. Make things bold and then indent the content.

it has paragraphs

* and
* bullets - these are bullets because their "parent" block (this one: <span class="roam-blockref">it has paragraphs</span> isn't bold

## And a nested heading

with more content

Embed content from a different page: 

<div markdown="1" class="roam-embed">


This page isn't published, but some of its blocks are referenced in <span class="roam-page">[Example Page](example-page)</span>.

* It has some bullets
* And another reference: <span class="roam-blockref">Another embedded block!</span>
* And another embed 

<div markdown="1" class="roam-embed">


Another embedded block!

</div>

</div>

```javascript
// some code
// this is javascript
```

An internal published block
* This block and its children are published as an "aside" type. The type name is included in the markdown frontmatter, so you can filter content into different sections of your site based on the type.

## Here's a table


| --- | **Someone Wise** | **Said** |
| --- | ---------------- | -------- |
| Socrates | The only true wisdom is in knowing you know nothing. |
| Hubbard | A friend is someone who knows all about you and still loves you. |
| Rowling | I mean, you could claim that _anything's_ real if the only basis for believing in it is that nobody's _proved_ it doesn't exist! |

## And an attribute table


<!-- Empty lines are left to allow Markdown processing on the cells -->
<div markdown="1" class="attr-table"><table>
<thead><th>

---

</th><th>

bar

</th><th>

foo

</th><th>

baz

</th></thead>
<tbody><tr><td>

Some data for the table

</td><td><div markdown="1" class="roam-block">

some bar

</div></td><td><div markdown="1" class="roam-block">

first foo linked to <span class="roam-page">[** Start Here **](start-here)</span>

</div><div markdown="1" class="roam-block">

another foo

</div></td><td></td></tr><tr><td>

Another row

</td><td><div markdown="1" class="roam-block">

with one bar

</div></td><td></td><td><div markdown="1" class="roam-block">

one baz with [Google](https://google.com) external link

</div><div markdown="1" class="roam-block">

[Retail](https://amazon.com)

</div></td></tr><tr><td>

A row showing nested attribute

</td><td><div markdown="1" class="roam-block">

one

</div><div markdown="1" class="roam-block">

two

</div></td><td></td><td><div markdown="1" class="roam-block">

it's a baz

</div></td></tr><tr><td>

An example attr page

</td><td><div markdown="1" class="roam-block">

something

</div></td><td><div markdown="1" class="roam-block">

this is a page

</div></td><td></td></tr></tbody></table></div>


An [external link to some interesting work](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm#Proof_of_correctness) which has a "#" symbol in the link.

<div markdown="1" class="roam-backrefs">

## 3 References

- [A Private Referenced Page](/content/a-private-referenced-page)
- [** Start Here **](/content/start-here)
- [An example attr page](/content/an-example-attr-page)

</div>