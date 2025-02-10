# Basics of Markdown

Writing in markdown is easy.
Unlike many other languages, it writes as it reads, since it was intended to be very human readable.
Those who use Discord know partly what markdown is, *with* **the** ***same*** `formatting` system at its core.

Below is that last sentence:

``Those who use Discord know partly what markdown is, *with* **the** ***same*** `formatting` system at its core.``

At the end of the day, markdown comes down to understanding the formatting, dealing with the quirks, and writing good above debugging and neat code; neat code is neat writing around these parts.

## Basics of Formatting

First, the headings.
Headings are denoted with a `#`, which is critical because there are rules to Markdown.

RULE 1
: Each file ended with a `.md` file extension, at least for JetBrains Writerside, MUST have a top-level heading.
: This is something like `# this is a top level heading`, on either the first or fourth line, more on that later.
: A file cannot contain two single hashes, only one can exist.
If you put two, it will implicitly convert the second and onward: `#` -> `##`.

Second, the text formatting.
As seen in the example above, italics, bolding, and a combination of both, as well as codeblocks are easy.
Do note that the `` `sample text` `` is just above the Tab key on your keyboard, or usually in the top left.
Dedicated code blocks are done with multiple lines surrounded by ```` ``` ````.

Third, whitespace.
Whitespace is the weirdest part of Markdown, and I'll go more in-depth on the jank later with Semantic Markup, but right now, here's the basics.
To account for the lack of explicit paragraph tags (technically), you have to declare paragraphs.
Below is how paragraphs are formatted.
```MD
# example page
paragraph 1
still paragraph 1

paragraph 2
still paragraph 2

<!-- will render as: -->
<!-- paragraph 1 still paragraph 1 -->
<!-- paragraph 2 still paragraph 2 -->
```
You absolutely need two enter hits to make a new paragraph, otherwise the program will add a space and continue on with the same one.
That doesn't mean that you won't use single breaks, I use them all the time.
Each sentence is its own break, since it makes the page a lot easier to write for.

## Lists

There are 3 kinds of lists that are the most common: unordered, ordered, and definition.

```MD
* entry 1
* entry 2
* entry 3

1. step 1
2. step 2
3. step 3

term 1
: definition 1

term 2
: definition 2

term 3
: definition 3
```