# Images

Images are commonly used within HTML, and, as such, have their own **\<img>** element tag.

The **\<img>** tag is empty and it contains attributes only, and does not have a closing tag.

The **src=""** attribute specifies the URL/Location of the image.
```html

<img src="path/to/myFile.jpeg">
```

There is also the **alt** attribute, which provides alternate text for an image. 
If the user cannot view an image (e.g. a slow internet connection, an error occurs in trying to find the image, the user is using a screen reader), the alt text will be displayed instead.
```html
<img src="qa_logo" alt="Logo of QA">
```
**(note: it is always best practice to include the alt tag to ensure good user experience. It has also become manadatory to use the alt attribute if the page is hosted publicly.)**

## Height and Width

You can apply styling to the width and height of an image in two ways - directly through HTML attributes, or through inline CSS styling.

### HTML styling

In HTML, the height and width attributes can be used to change the image size:
```html
<img src="qa_logo"alt="Logo of QA" width="128" height="128">
```

### CSS styling

The width and height CSS style attributes can be applied inline by using the style HTML attribute:
```html
<img src="qa_logo" alt="Logo of QA" style="width:128px;height:128px;">
```

The syntax is slightly different as a result of the switch from HTML to CSS.

# Hyperlinks

Hyperlinks are used to navigate within Web pages; both internally to pages within the site's domain, and externally to outside sources.

Irrespective of whether a link navigates internally or externally, the syntax for adding a hyperlink to a page is similar:
```html
<!-- Navigates within the website e.g. link to homepage. -->
<a href="/home">Home page</a>
<!-- links to an external website e.g. www.google.com -->
<a href="https://www.google.com">Google homepage</a>
```

Hyperlinks can nest other elements, such as images. Website logos commonly navigate to the site's homepage:
```html
<a href="/home.html">
<img src="logo_of business.png" alt="Image of logo to navigate home" style="width:42px;height:42px;>
</a>
```

