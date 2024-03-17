# Headings and paragraphs

A major part of HTML is the content that is written inside the page! 
For this, there are 2 very important tags - headings and paragraphs.

Headings tags are typically used for the title of a page or post, and it is the first header visible on a page. 
Paragraphs are used for blocks of text, making it the most accesible way of block-displaying content onto an HTML page.

## Headings

Headings are titles or subtitles that you want to display on a Web page. 
The smallest heading starts at **\<h6>** and the largest heading is **\<h1>**. 
The default heading size is **\<h4>**.

Below are all of the tags required for the different heading sizes:
```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4 (this is the default heading size)</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## Paragraphs

A paragraph is usually a block of text that will always start on a new line. We define a paragraph using the **\<p>** tag.

The formatting for a **\<p>** tag is unique:
* The browser automatically adds some white space (margin) before and after a paragraph.
* Paragraphs appear single-spaced and on a single line - all other space is omitted.
* To circumvent the above, using a line break (**\<br>**) ensures that text is on a new line.

```html
<p>This is a paragraph</p>
<!-- Output: "This is a paragraph" -->
<p>
This
is
another
paragraph</p>
<!-- Output: "This is another paragraph" -->

<p>This <br> has <br> breaks</p>
<!-- output:
"This
has
breaks" 
-->
```
