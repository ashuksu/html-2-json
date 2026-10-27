# html2json

`html2json` is a lightweight HTML parser that converts HTML strings into a custom AST JSON representation without using `DOMParser`.

## Features

- Tokenizes HTML and builds a hierarchical tree.
- Supports nested elements, attributes, comments, and void elements.
- Handles DOCTYPE, whitespace, and `<script>` and `<style>` content.
- Includes sample HTML files for testing.

## Usage

```
import { html2json } from './html2json.js';

const result = html2json('<div class="example">Hello</div>');
console.log(result);
```

## Demo

[Live Demo](https://ashuksu.github.io/html-2-json/)
