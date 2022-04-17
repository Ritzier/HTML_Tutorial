# HTML_Tutorial

## Sample Format
```html
<html>
  <head>
  </head>
  
  <body>
  </body>
</html>
```
## Body:

### Heading:
```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

### Formatting:
* br: Line break
* strong: Bold
* em: Italic
* mark: Highlight with yellow
* sub: Font size smaller
* del: Strikeout
* q: Quotation
```html
<p>This is a paragraph <br> This is another paragraph</p>
<p>This is a <strong>TEST</strong></p>
<p>This also a <em>Test</em></p>
<p><mark>Important!!!</mark></p>
<p><del>Strikeout</del><p>
<p><q>test</q></p>

<!--><p>This is a Comment<p><-->
```

### Links:
```html
<a href="https://github.com">Github Link
```

### Images:
* alt: When image failed loading, will display alt text
```html
<img src="Image/first.png" alt="Bing Chilling" width="1920" height="1080">]\\\\\\\\\\]\\\
```
### Lists:
```html
<li>Nmae: </li>
<li>Age: </li>
```

## Table:
### Format:
* table: Defines a table
* th: Header cell in a table
* tr: Row in a table
* td: Cell in a table
* caption: Table Caption
* colgroup: Group columns in a table for fomatting
* col: Column properties for each column within a colgroup element
* thead: Header content in table
* tbody: Body content in table
* tfoot: Footer content in a table

## CSS (style):
```html
<p style="color:red">Hi!</p>
```
### with global, id, class:
```html
<html>
<head>
    <style>
        p {
            color: green;
        }

        .p {
            color: blue;
        }

        #p {
            color: yellow;
        }
    </style>
</head>
<body>
    <p>Paragraph1</p>
    <p id="p">Paragraph2</p>
    <p class="p">Paragraph3</p>
</body>
</html>
```

### Formatting:
* color
* background-color
* text-shadow
* width
* height
* text-align
