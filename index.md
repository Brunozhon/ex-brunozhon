## Welcome to my repostory

This file is edited at `index.md`. You can copy the link to go to the repo:

```
https://github.com/Brunozhon/ex-brunozhon/
```

Or use this link to go to my website:

```
https://brunozhon.github.io/ex-brunozhon/
```

### Want to meet me?

![Me!](https://brunozhon.github.io/image.jpg)

Just visit [my webpage](https://brunozhon.github.io)

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
### Why markdown?

Markdown provides easy syntax for headings, paragraphs, and much more!

Markdown:

```markdown
# This is a heading

This is a paragraph

[Hello links!](https://brunozhon.github.io)

![Hello images!](https://brunozhon.github.io/image.jpg)
```

HTML:

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
    <p><a href="https://brunozhon.github.io">Hello links!</a></p>
    <img src="https://brunozhon.github.io/image.jpg" alt="Hello images!">
  </body>
</html>
```

### Markdown will highlight things depending on the languge defined after the three ticks (\`\`\`)

HTML \`\`\`html:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My first webpage</title>
    <link rel="stylesheet" href="style.css">
    <style>
      /*Some styles*/
    </style>
  </head>
  <body>
    <h2>My webpage</h2>
    <p>This webpage is styled with the hacker theme</p>
    <script src="script.js"></script>
    <script>
      //Some code
    </script>
  </body>
</html>
```

CSS \`\`\`css:

```css
h1,h2,h3,h4,h5,h6 {
  color: #00ff00;
}
body {
  magrin: 0px;
  padding: 0px;
}
.bruno {
  padding: 16px; 
}
.bruno.bruno-no-padding {
  padding: 0px;
}
.bruno.bruno-no-magrin {
  magrin: 0px;
}
.bruno.bruno-clear-magr-padd {
  padding: 0px;
  magrin: 0px;
}
/*Other styles*/
```

JSON \`\`\`json:

```json
{
  "name":"John Doe",
  "age":26,
  "coding_area":"GitHub"
}
```

CoffeeScript (:coffee:Script) \`\`\`coffeescript

```coffeescript
count = (c) ->
  return c + 1

console.log count 1
```
