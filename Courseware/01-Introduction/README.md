# Introduction

**Hypertext Markup Language**, or HTML, is the recognised standard language for creating documents designed to be displayed in a web browser. 
Currently, the latest standard is **HTML5**. 

HTML is often used in conjunction with *Cascading Style Sheets (CSS)* and *JavaScript (JS)*, to style and add further functionality to a page.

## An Example HTML Page

Below is a very simple HTML document showing three main elements: **DTD** (or Document Type Definition), **<head>**, and **<body>**:
```sql
<!DOCTYPE html> <!-- HTML5 Document Type Definition -->
<html>
    <head>
        <title>QA Talent HTML</title>
    </head>

    <body>
        <p>Welcome to QAT HTML!</p>
    </body>
</html>
```

## Document Type Definition (DTD)

The document type definition is **required** to be placed at the top of every HTML document. 
It is used to inform the browser about the version of HTML that is used in the document.

Have a look at the below examples of how to declare a DTD:

**HTML 4 Strict**
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0//EN" "http://www.w3.org/TR/html4/strict.dtd">
```

**HTML 4 Transitional**
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN" "http://www.w3.org/TR/REC-html4/loose.dtd">
```

**HTML 5**
```html
<!Doctype html>
```

## Head

The **<head>** tag is used to define metadata (data about the data) for a HTML document, such as scripts, document titles, and more. 
This data is not displayed on the page.

|   Tag    |                                           Description                                           |
|:--------:|:-----------------------------------------------------------------------------------------------:|
| <title>  |        Defines title of document for browser tab, favourites and search engine results          |
| <style>  |                          Defines style information about this document                          |
|  <link>  |                    Defines where external style sheets should be linked from                    |
|  <meta>  |        Specifies the page’s character set, description, keywords, author, viewport, etc.        |
| <script> | Defines client-side JavaScript (although more commonly included as last element of (**<body>**) |
|  <base>  |                  Specifies base URL and target for all relative URLs in a page                  |
