<h1 align="center"><code>css-uncomment.js</code></h1>

<p align="center">Remove CSS comments from a string</p>

## ⚙️ Installation

```js
npm i css-uncomment
```

**CDN Links:**
- https://cdn.jsdelivr.net/npm/css-uncomment@1.0.0/css-uncomment.js
- https://www.unpkg.com/css-uncomment@1.0.0/css-uncomment.js

## 📖 Usage

#### ◎ Import

```js
// ES6
import cssUncomment from "css-uncomment";

// commonjs
const cssUncomment = require("css-uncomment");
```

#### ◎ Example

```js
const string = cssUncomment(`
    /* start of my very cool css styling */
    div {
        color: red; /* changes color to red */
    }
`);

console.log(string);
```

---

[Support me on Patreon](https://www.patreon.com/axorax) - 
[Check out my socials](https://github.com/axorax/socials)