# Tables

Tables in general are a great way of displaying data. 
The use of tables gives us a great way to show data, making it easy to understand and be able to pick out important information.

## Creating a HTML Table

When working with HTML tables we need to ensure that all other tags associated with **\<table>** are wrapped around them.

* After the opening **\<table>** we then create a table row **\<tr>**.
* We then have the option to either use **\<th>** or **\<td>**.
    * **\<th>** - Used for table heading (make the heading bold).
    * **\<td>** - Used for entering data e.g. score is 50.
    
    
Below is an example of a very simple table which does not contain any data:
```html
<!DOCTYPE html>
<html>
<body>
<h2>Heading HTML Table</h2>
<table>
  <tr>
    <th>Student Name</th>
    <th>Subject</th>
    <th>Score</th>
  </tr>
```

|       Tag       |                     Description                     |
|:---------------:|:---------------------------------------------------:|
|    **\<tr>**    |                      Table row                      |
|    **\<td>**    |           Table data (i.e. a normal cell)           |
|    **\<th>**    |         Table heading (i.e. a header cell)          |
| **\<caption>**  |                    Table caption                    |
|  **\<thead>**   |          Groups header content in a table           |
|  **\<tbody>**   |           Groups body content in a table            |
|  **\<tfoot>**   |          Groups footer content in a table           |
| **\<colgroup>** |    Specifies one or more columns for formatting     |
|   **\<col>**    | Specifies column properties for each column within  |

```html
<!DOCTYPE html>
<html>
<body>
<h2>Basic HTML Table</h2>
<table>
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Bill</td>
    <td>Steves</td>
    <td>33</td>
  </tr>
</table>
</body>
</html>
```

Will produce the following:

| First Name | Last Name | Age |
|:----------:|:---------:|:---:|
|    Jill    |   Smith   | 50  |
|    Bill    |  Steves   | 33  |







