# Hello, contributors.

This file is exclusively for you guys looking at the guts and literally nobody else, so don't add it to the actual github pages.

What you're seeing is Markdown, and yes, the whitespace is deliberate.

## Paragraphs
That right there is a heading, you've got 6 hashtags to go from, in html it would be h1-h6.

This is another paragraph.
This *isn't* another paragraph, it'll render something like this:

<!-- This is another paragraph. This *isn't* another paragraph, it'll render something like this: -->

However, it does automatically put spaces
so this is entirely valid:

<!-- However, it does automatically put spaces so this is entirely valid: -->

## Text Formatting
*italics*
_alternate italics_
<!-- they do the same thing -->

**bold**
***bold & italic***

* bullet
* points

1. numbered
2. points
3. they
4. work
5. well

`inline codeblock`
```
codeblock
but for more lines
yeah
```

$inline LaTeX$

$$
display environment latex
$$

## The other half

<p>This is semantic markup, a breed of XML.</p>
<p>For those using HTML, this should look VERY familiar.
That's because it is.</p>

## Tabs

<tabs>
<!-- gotta have the tabs tag -->
<tab id="unique-id1" title="tab 1">

your content goes in here

</tab>
<tab id="e" title="another explanation">

markdown and semantic markup work together weirdly
take a look at the below block for why

```
<example-tag> (this isn't real)
*this won't render right*
</example-tag>

<ee>

*this will*
</ee>
```

always have a line break after a tag if you wanna use markdown formatting
just in case always do one before and after the markdown (it looks cleaner)

</tab>

</tabs>

## Tables

| column | column2  |
|--------|----------|
| this   | is       |
| a      | markdown |
| table  | yeah     |

## More information

this is an image:

![alt text](completion_procedure.png)

images go in the images folder

this is a link:

[link text](https://wc-iii.github.io/MRBob)

you can even do links to other topics:

[another topic](Before-You-Start-Coding.md)

`<link-summary>` helps with those topic links (it'll show you some text if you hover over the link that's a summary)

`<tldr>` is usually an abstract type thing

```
---
switcher-label: example
---
```

that's for the top-left / top-right switchers

### example heading 1 {switcher-key="1"}

### example heading 2 {switcher-key="2"}

term
: definition
: added text or something
continued paragraph

that's a definition list, they're helpful for terms

> this is a gray note

modifiable with `{style="note"}` or `{style="warning"}`

procedures are cool

<procedure>
<step>
step 1
</step>
<step>
step 2
</step>
<step>
these are instructions for something and should be used as such
</step>
</procedure>