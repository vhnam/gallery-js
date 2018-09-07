# gallery-js
Photo Gallery likes Facebook Friendship's Day

## How to use

### JS
```js
// index.js
var photos = [
    {
        src: 'http://lorempixel.com/640/480/',
        title: 'Lorem ipsum'
    }, {
        src: 'http://lorempixel.com/640/480/',
        title: 'Optio quos qui illo error'
    }
];

var gallery = new Gallery('root', 3000, photos);
```

### HTML
```html
<html>
    <head>
        <link rel="stylesheet" href="../gallery.css">
    </head>
    <body>
        <div id="root"></div>
        <script src="../gallery.js"></script>
        <script src="index.js"></script>
    </body>
</html>
```
