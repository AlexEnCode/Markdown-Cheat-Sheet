# 📄 Markdown Cheat Sheet

---

## Headers
```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

---

## Bold and Italic Text
```markdown
**Bold** or __Bold__
*Italic* or _Italic_
***Bold and Italic*** or ___Bold and Italic___
```

---

## Lists
### Unordered List
```markdown
- Item 1
- Item 2
  - Subitem
    - Sub-subitem
```

### Ordered List
```markdown
1. Item 1
2. Item 2
   1. Subitem
   2. Subitem
```

---

## Links and Images
### Link
```markdown
[Link Text](https://example.com)
```

### Image
```markdown
![Alt Text](https://example.com/image.jpg)
```

---

## Blockquotes
```markdown
> This is a blockquote.
```

---

## Code
### Inline Code
```markdown
Here is `inline code`.
```

### Code Block
\`\`\`language
// Example in JavaScript
console.log("Hello, world!");
\`\`\`

---

## Tables
```markdown
| Column 1  | Column 2  |
|-----------|-----------|
| Data 1    | Data 2    |
| Data 3    | Data 4    |
```

---

## Horizontal Line
```markdown
---
```

---

## Task Lists
```markdown
- [x] Completed Task
- [ ] Incomplete Task
```

---

## Emojis (on supported platforms)
```markdown
:smile: :heart: :+1:
```

---

## Line Break
Add two spaces at the end of a line  
like this.

---

## Colors and Text Styles using HTML

<span style="color:blue">This text is blue</span>
<span style="color:red; font-weight:bold">This text is bold and red</span>

---

## Forms using HTML

<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <input type="submit" value="Submit">
</form>

---

## Embedding Images with Different Sizes
To control the size of images, HTML is again helpful.

<img src="https://example.com/image.jpg" alt="Description" width="300" height="200">

---

##  Embedding Videos


<iframe width="560" height="315" src="https://www.youtube.com/embed/your-video-id" frameborder="0" allowfullscreen></iframe>


---

## Adding Comments

<!-- This is a comment and will not appear in the rendered Markdown -->


---

## Advanced Tables with HTML


<table>
  <tr>
    <th rowspan="2">Header 1</th>
    <th colspan="2">Header 2</th>
  </tr>
  <tr>
    <td>Subheader 1</td>
    <td>Subheader 2</td>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
    <td>Data 3</td>
  </tr>
</table>


---

## Using Platform-Specific Features

- **GitHub Flavored Markdown (GFM)**, which includes features like task lists, tables, and syntax highlighting.
- **Mermaid Diagrams** for flowcharts and other visualizations in Markdown (supported on platforms like GitHub and GitLab).


```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


---

Markdown has some limitations, especially when it comes to styling with colors or shapes, as it is primarily designed for simplicity and readability. However, there are a few ways to extend Markdown's capabilities using HTML and platform-specific features.
Markdown can be greatly extended by mixing in HTML for added control over styling and layout. However, support for these features may vary based on the platform where the Markdown is rendered.
With this cheat sheet, you’re all set to create beautiful Markdown documents effortlessly! 🎉
