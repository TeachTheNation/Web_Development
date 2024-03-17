# Attributes

HTML attributes are used to provide additional information about HTML elements.
* All HTML elements can have attributes.
* Attributes provide additional information about elements.
* Attributes are always specified in the start tag.
* Attributes usually come in name/value pairs - **name="value"**.

It is best practice (according to the W3C) to use lowercase for attribute names and values, and to "quote" values in HTML. 
For stricter document types, like XHTML, these practices become mandatory.

## \<html> tag attributes
We should always include the **lang** attribute inside the **\<html>** tag, to declare the language of the Web page. 
This assists search engines and browsers.

The following example specifies English as the language:
```html
<!DOCTYPE html>
<html lang="en">
    <body>
        ...
    </body>
</html>
```

We can also add country codes to the **lang** attribute. 
The first two characters define the language of the HTML page, and the last two characters define the country.

The following example specifies the British dialect for English:
```html
<!DOCTYPE html>
<html lang="en-GB">
<body>
...
</body>
</html>
```

### \<a> attributes

The **\<a href>** tag is used to define a hyperlink, with the attribute being used to specify the URL the link goes to:
```html
<a href="https://www.qa.com">Go to QA homepage.</a>
```

### \<img> attributes

The **\<img>** tag is used to display an image in an HTML page. 
The src attribute specifies the path to the image to be displayed on the page:
```html
<img src="qa_logo.jpg">
```

The mandatory alt attribute for the **\<img>** tag specifies an alternate text for an imag if it can't be displayed. 
This can be due to slow connection, or an error in the **src** attribute, or if the user uses a screen reader.

Below is a full exmaple of using the **\<img>** tag with supporting **alt** attribute:
```html
<img src="qa_logo.jpg" alt="qa brand logo">
```

### \<p> attributes

The style attribute is used to add inline CSS styles to an element, such as color, font, size, and more.

However, it is better practice to link an external CSS document.
```html
<p style="color:red;">This is a red paragraph.</p>
```

The title attribute defines some extra information about an element. 
The value of the title attribute will be displayed as a tooltip when you mouse over the element:
```html
<p title="I'm a tooltip">This is a paragraph.</p>
```















