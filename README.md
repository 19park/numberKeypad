# numberKeypad
demo : https://vibrant-northcutt-d99c0f.netlify.com/demo.html


Usage
-----
* Include `jquery.numberKeypad.css`  at the bottom after bootStrap.

  ```
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
  <link rel="stylesheet" type="text/css" href="jquery.numberKeypad.css">
  ```

* Include `jquery.numberKeypad.js` at the bottom after jQuery.

  ```
  <script type="text/javascript" src="http://code.jquery.com/jquery-1.11.0.min.js"></script>
  <script type="text/javascript" src="jquery.numberKeypad.js"></script>
  ```

* Use `numberKeypad` function on jQuery object.

  ```
  $(document).ready(function() {
      $('#keypad').numberKeypad();
  });
  ```

Advance options
---------------
You can customize the plugin by providing a hash with options on initialization. eg:

```
$(document).ready(function() {
    $('#keypad').numberKeypad({
        wrap: '.wrapper',
		arrKeys: ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'x', 'j', 'ok'],
        login: false
    });
});
```

Default options:

```
{
	wrap: '.wrapper',
	arrKeys: [1, 2, 3, 4, 5, 6, 7, 8, 9, 'x', 0, 'ok'],
	login: false
}
```
