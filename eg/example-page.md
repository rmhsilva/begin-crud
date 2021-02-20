---
title: Example Page
type: blog
slug: example-page
date: 2021-02-09T08:32:58.126000
---

This page will be categorised as a "blog" item. So will <span class="roam-page">[[[A Second Published Page]]](a-second-published-page)</span>.

Things marked (WIP) are not live on [ivywrite.io](https://ivywrite.io) yet.



## Roam headings work as expected 

They're converted into the expected markdown heading level.



A bulleted list:

* with a **bold bit**, and a hashtag 
* and a linked page February 8th, 2021
* with a nested bullet list

    - point 1 <span class="roam-highlighted">is highlighted</span> in roam and <span class="roam-highlighted">so is this bit</span>
    - point 2 _is italic_ in roam



A block ref: <span class="roam-blockref"><span class="roam-blockref">This page will be categorised as a "blog" item. So will <span class="roam-page">[[[A Second Published Page]]](a-second-published-page)</span>.</span></span>



# Indent-style heading

AKA [Markus](https://dacapo.io) style headings. Make things bold and then indent the content.

it has paragraphs

* and
* bullets - these are bullets because their "parent" block (this one: <span class="roam-blockref"><span class="roam-blockref">it has paragraphs</span></span> isn't bold

## And a nested heading

with more content



Embed content from a different page: 

<div class="roam-embed">


This page isn't published, but some of its blocks are referenced in <span class="roam-page">[[[Example Page]]](example-page)</span>.

* It has some bullets
* And another reference: <span class="roam-blockref"><span class="roam-blockref">Another embedded block!</span></span>
* And another embed 

<div class="roam-embed">


Another embedded block!

</div>

</div>





```javascript
// some code
// this is javascript
```



An internal published block
* This block and its children are published as an "aside" type. The type name is included in the markdown frontmatter, so you can filter content into different sections of your site based on the type.



## Here's a table (WIP)


| --- | **Someone Wise** | **Said** |
| --- | ---------------- | -------- |
| Socrates | The only true wisdom is in knowing you know nothing. |
| Socrates | um |
| Hubbard | A friend is someone who knows all about you and still loves you. |
| Rowling | I mean, you could claim that _anything's_ real if the only basis for believing in it is that nobody's _proved_ it doesn't exist! |






| --- | a | 1 |
| --- | - | - |
| a | 2 |
| b |





## And an attribute table (WIP)



<div class="attr-table">

| --- | bar | foo | baz |
| --- | --- | --- | --- |
| Some data for the table | some bar | another foo | |
| Another row | with just a bar | | and a baz |

</div>



