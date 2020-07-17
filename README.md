# [typewriter.js](https://github.com/reesericci/typewriter.js)
A super-simple library to type-out text with javascript.

### Adapted from [this codepen](https://codepen.io/hi-im-si/pen/DHoup)

## How to use

#### Import the library at the bottom of your body section in the HTML document.

one-liner: `<script src="https://reesericci.github.io/typewriter.js/typewriter.js"></script>`

e.g.

```
<html>
<head>
...
</head>
<body>
...
<script src="https://reesericci.github.io/typewriter.js/typewriter.js"></script>
</body>
</html>
```

#### Add the class and data to a html text tag (p, h1, h2, h3, etc)

class: `typewrite`

data:
  
  time (amt of time for typing): `type-time='time in ms'`
  
  data (the text being typed): `type-data='[ "Text #1" ], [ "Text #2, Text #1 got erased to show Text #2" ]'`

e.g.

```
<h1 class="typewrite" type-time='1000' type-data='[ "This text got typed" ], [ "That old text got erased, this is the new text!"]'></h1>
```
