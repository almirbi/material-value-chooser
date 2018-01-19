[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/almirbi/material-value-chooser)

# \<material-value-chooser\>

An input element that makes it easier for the user to input a value from a pre-defined set of values which are often used. E.g. if entering a score of a football match, chances are high the number to be used will be an integer from 0 - 5. Instead of using the keyboard and additional tap/clicks the user can input a number more efficiently. Also, poker.

You may import `iron-icons` to use with this element and set the icon property from the [iron iconset](https://www.webcomponents.org/element/PolymerElements/iron-icons)

Set the values by setting the values property of the element, and then pick up the chosen value with the value property.

Icon and label property cannot be used at the same time, choose one.

Opened property expands/collapses the value chooser.

```html
<material-value-chooser icon="add" label="+" values="[[values]]" value="{{value}}" opened="{{opened}}"></material-value-chooser>
```

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="../web-animations-js/web-animations-next-lite.min.js"></script>
    <link rel="import" href="material-value-chooser.html">

    <div class="container">
      <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->

```html
<material-value-chooser></material-value-chooser>
```
