# Lists

In HTML, we can use **lists** to store display information. 
These lists fall into three broad types: **Unordered**, **ordered** and **description** lists.

## Unordered lists

Unordered lists use the **\<ul>** and **\</ul>** tags. 
Every list item is then contained in this element using the **\<li>** and **\</li>** tags.
```html
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
</ul>
```

This yields the following:
- List item 1
- List item 2

We can also add stylistic customisation to these lists. 
For instance, rather than using the default bullet points, the below example replaces bullets with circles:
```html
<h1>Shopping list</h1>
<ul style="list-style-type: circle;">
    <li>Cup</li>
    <li>Tea bag</li>
    <li>Hot water</li>
    <li>Milk</li>
</ul>
```
Some of the other options we have are below:

| Value  |                    Description                    |
|:------:|:-------------------------------------------------:|
| disc   | Sets the list item marker to a bullet (default)   |
| circle |       Sets the list item marker to a circle       |
| square |       Sets the list item marker to a square       |
|  none  |         The list items will not be marked         |

## Ordered list

Ordered lists use the **\<ol>** and **\</ol>** tags, with every list item contained in this element using the **\<li>** and **\</li>** tags.

Ordered lists are simply numbered lists, starting from 1 and incrementing until there are no more list items left.
```html
<ol>
    <li>Cup</li>
    <li>Tea bag</li>
    <li>Hot water</li>
    <li>Milk</li>
</ol>
```

This yields the following:
1. Cup
2. Tea bag
3. Hot water
4. Milk

Ordered lists can take the start attribute to set the number at which the order begins:
```html
<ol start=5>
  <li> Coffee </li>
  <li> Tea </li>
  <li> Water </li>
</ol>
```

This yields the following:
5. Coffee
6. Tea
7. Water

We can also use the type attribute, which can allow us to customise the ordered list further. Here, we order the list by capital letters:
```html
<ol type="A">
  <li> Coffee </li>
  <li> Tea </li>
  <li> Water </li>
</ol>
```

A. Coffee
B. Tea
C. Water

**type** can be assigned several predefined ordering styles:

|   Type    |                         Description                          |
|:---------:|:------------------------------------------------------------:|
| type="1"  |   The list items will be numbered with numbers (default)     |
| type="A"  |    The list items will be numbered with uppercase letters    |
| type="a"  |    The list items will be numbered with lowercase letters    |
| type="I"  | The list items will be numbered with uppercase roman numbers |
| type="i"  | The list items will be numbered with lowercase roman numbers |









