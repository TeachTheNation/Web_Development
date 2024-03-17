# CSS

**Cascading Style Sheets (CSS)** is a styling language that is used to illustrate the look, style, and format of a document written in any markup language. It is most commonly used to style and organize the layout of Web pages. 
**CSS3** is the latest version.

CSS rules can be applied to multiple pages at once, allowing for easy maintainability. Styling can be adjusted in a single document, which **cascades** to impact several files at once.

This differs from inline styling with HTML which, due to its tight coupling together of web page architecture and styling, has poor maintainability.

## Inline styles

Inline styling is typically used if one single HTML page has a unique style.

The inline style is defined by the **style** label inside the head section of the element you wish to apply the styling to:
```html
<p style="color:red;">Inline CSS</p>
```

This style is only scoped to the specific element whose tag it is defined in.

## Embedded Style Sheets

Style sheets can be embedded within an HTML document within **\<style>** container tags. 
The **\<style>** tag has a type attribute which is text/css for CSS.
```html
<style type=“text/css”>
    h1 {font-size:15pt;font-weight:bold}
    p {font:bolditalic 12pt/20pt Times,serif}
</style>
```

## External Style Sheets

The most effective way to implement CSS is through an external style sheet, saved in **.css** format.

Each HTML page must include a href reference to the external style sheet file inside the **\<link>** element.

Here, it is stored in the same folder as the .html file:
```html
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" type="text/css" href="myFile.css">
    </head>
    <body>
        <h1>This is a heading</h1>
    </body>
</html>
body {
  background-color: blue;
}
h1 {
  color: navy;
  margin-left: 20px;
}
```











