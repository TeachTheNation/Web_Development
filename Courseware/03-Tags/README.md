# Tags

When working with HTML, we use tags around our code to create different functionality. 
Tags tend to be come in pairs - one when opened (e.g. **<p>**), and one when closed (e.g. **</p>**).

There are exceptions where some tags are self-closing (such as the tag for an image **<img>**), but the majority use opening and closing tags.

## Paired and self-closing tags

```html
<h1>This is a large heading</h1>
<h6>This is a small heading</h6>
<p>This is a paragraph</p>
```

Below is some example HTML for a self-closing tag:
```html
<img src="my_image"  alt="alt text for my image" >
<br/>
<hr/>
```

It is important to ensure that tags are closed in the order in which they are opened.

The below example is incorrect as the </b> tag is closed after the </p> tag:
```html
<p>This is some text and this is <b>important in bold</p> </b>
```

This is the correct way to open and close tags:
```html
<p>This is some text and this is <b>important</b>in bold</p>
```

If you do not close your tags in the correct structure, the HTML DOM will simply not understand what you're trying to do due to an issue with the scope of your tags. 
This is very similar to programming and the ordering of closed brackets!

## Required and optional attributes

There are some tags in HTML that will also contain attributes; some are required and some are optional:
```html
<h1 id="myHeading"></h1>
<!-- This has an optional id attribute -->
<img src="myFileName"  alt="myFileName alt text">
<!-- This has a mandatory src attribute -->
```









