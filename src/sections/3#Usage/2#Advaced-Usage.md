### Advanced Usage

Using the module version of Doc Ez gives you direct access to the generated file tree as well as the HTML allowing you to parse it and compile it however you like.

```javascript
const docez = require("docez");

const { tree, html } = docez({
    input  : "you/input/dir",
    output : "your/output/dir",

    // Don't write out to output/index.html
    write  : false,
});

const { nav, content } = html;
````