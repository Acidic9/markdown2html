# Markdown2HTML
Safely convert your markdown code to HTML escaping all dangerous markdown whithout damaging the overall markdown code.

### Installing
Copy markdown2html.min.js into your project and link it in your HTML document with
```js
<script rel="/js/markdown2html.min.js"></script>
```

### Usage
Once you have imported markdown2html.min.js, use the single function ``markdownToHTML(markdown)`` to convert any markdown to HTML code.

###### Example usage
```js
var markdown = "This text is in **Markdown**";
var html = markdownToHTML(markdown);
```

### Sources
This whole package was not written by just me... I used the [marked](https://github.com/chjj/marked) package on github along with a custom made function.