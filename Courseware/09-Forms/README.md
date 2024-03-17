# Forms

Forms in HTML are used to collect user input, which can then be sent to another page or sent to a server for processing.

We create a form by using **\<form>** and **\</form>** tags, nesting our form elements within it.

Within the first <form> tag we also specify the action and the method:
* **Action** - URL to open / action to execute upon form submission
* **Method** - How the information is passed to the server:
  * **GET**: Appends the arguments to the action URL and opens it as if it were an anchor 
  * **POST**: Posts the information to whichever URL the form points to

```html
<form method="post" action="scripts/subscribe.pl">
  <!-- Some elements -->
</form>
```

## Form Options

### Text Input

Textual input is the most common form element, which allows us to enter text into a field:
```html
<form method="post" action="scripts/subscribe.pl">
  Please enter your name:
  <input type="text" name="UserName"/>
</form>
```

The placeholder attribute assigns temporary text to the field, which will be wiped away when the user starts typing:
```html
<form method="post" action="scripts/subscribe.pl">
  Please enter your name:
  <input type="text" placeholder="Enter Username" name="UserName"/>
</form>
```

The value attribute assigns default information to the field, which might be replaced by the user:
```html
<form method="post" action="scripts/subscribe.pl">
  Please enter your name:
  <input type="text" value="John_Doe123" name="Username"/>
</form>
```

### Buttons

Buttons allow us to interact with forms, though there are three distinct types of thing which a user might call a button:
* **submit**: sends information in the form using whichever **action** is defined in the **\<form>** tag
* **reset**: sets the entire form to its initial state, using default settings if assigned
* **button**: acts as a trigger for any client-side script assigned to it

In the below example, the **submit** button will call the **subscribe.pl** script defined in the **action** attribute of the **\<form>**, the **reset** button will clear the form, and the standard **button** will do nothing:
```html
<form method="post" action="scripts/subscribe.pl">
  Please enter your name:
  <input type="text" name="UsrName"/>
  <br/>
  <button type="submit" name="OKBtn" value="OK" />
  <button type="reset" name="ResetBtn" value="Reset" />
  <button type="button" >Click me</button>
</form>
```
