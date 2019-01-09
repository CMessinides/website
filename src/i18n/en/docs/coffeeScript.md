# CoffeeScript

_Supported extensions: `coffee`_

(CoffeeScript)[https://coffeescript.org/] is language that compiles to JavaScript, with syntax and features inspired by Ruby and Python. You can import CoffeeScript modules with no additional configuration. Parcel will install the [`coffeescript` package](https://www.npmjs.com/package/coffeescript) if necessary and use it to transform your CoffeeScript into JavaScript.

```html
<!-- index.html -->
<html>
<body>
  <script src="./index.coffee"></script>
</body>
</html>
```

```coffee
# index.coffee
message = "Hello world!"
console.log message
```
