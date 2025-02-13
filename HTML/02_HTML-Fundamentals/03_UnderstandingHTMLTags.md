### **HTML Tags and Attributes**

In HTML, **tags** are used to define elements in the structure of a webpage, and **attributes** are used to provide additional information about those elements.

### **HTML Tags:**
Tags are enclosed in angle brackets `< >`. They are the building blocks of an HTML document. Every HTML element usually consists of an opening tag, content, and a closing tag.

#### **Basic Structure of Tags:**
```html
<tagname>content</tagname>
```
- **Opening tag**: `<tagname>`
- **Closing tag**: `</tagname>` (Note: the closing tag has a forward slash `/` before the tag name.)

Some tags are self-closing (like `<img />` or `<br />`) and do not have a closing tag.

#### **Common HTML Tags:**

1. **`<html>`**: Defines the root of an HTML document.
   ```html
   <html>
       <!-- content here -->
   </html>
   ```
   
2. **`<head>`**: Contains meta-information about the document, like title, character encoding, and links to stylesheets or scripts.
   ```html
   <head>
       <title>My Webpage</title>
   </head>
   ```

3. **`<title>`**: Specifies the title of the document, which appears in the browser tab.
   ```html
   <title>Page Title</title>
   ```

4. **`<body>`**: Contains the content of the webpage visible to users.
   ```html
   <body>
       <h1>Welcome!</h1>
       <p>This is a paragraph.</p>
   </body>
   ```

5. **`<h1> to <h6>`**: Define headings, with `<h1>` being the largest and `<h6>` the smallest.
   ```html
   <h1>Main Heading</h1>
   <h2>Subheading</h2>
   ```

6. **`<p>`**: Defines a paragraph of text.
   ```html
   <p>This is a paragraph.</p>
   ```

7. **`<a>`**: Creates a hyperlink to another webpage or resource.
   ```html
   <a href="https://www.example.com">Click here</a>
   ```

8. **`<img>`**: Embeds an image into the page. This is a self-closing tag.
   ```html
   <img src="image.jpg" alt="Description of image" />
   ```

9. **`<ul>` and `<ol>`**: Define unordered (bulleted) and ordered (numbered) lists, respectively.
   ```html
   <ul>
       <li>Item 1</li>
       <li>Item 2</li>
   </ul>
   ```

10. **`<div>`**: Used to group block-level elements together. It has no semantic meaning, but is commonly used for layout and styling.
    ```html
    <div>
        <h2>Section Title</h2>
        <p>This is a section.</p>
    </div>
    ```

11. **`<span>`**: Used to group inline elements together, often for styling purposes.
    ```html
    <span style="color: red;">This is a red text.</span>
    ```

### **HTML Attributes:**
Attributes provide additional information about an HTML element. They are placed within the opening tag and come in name-value pairs.

#### **Syntax of Attributes:**
```html
<tagname attribute="value">content</tagname>
```

#### **Common HTML Attributes:**

1. **`id`**: Uniquely identifies an element on the page.
   ```html
   <div id="header">Header Content</div>
   ```

2. **`class`**: Specifies a class for an element, which can be used for styling or selecting elements in JavaScript.
   ```html
   <p class="intro">This is an introductory paragraph.</p>
   ```

3. **`href`**: Specifies the destination URL for an anchor (`<a>`) tag.
   ```html
   <a href="https://www.example.com">Go to Example</a>
   ```

4. **`src`**: Specifies the source for an image or media file.
   ```html
   <img src="logo.png" alt="Logo" />
   ```

5. **`alt`**: Provides a textual description for an image, which is displayed if the image cannot be loaded.
   ```html
   <img src="logo.png" alt="Company Logo" />
   ```

6. **`style`**: Applies inline CSS styles to an element.
   ```html
   <p style="color: blue;">This text is blue.</p>
   ```

7. **`target`**: Specifies where to open the linked document (commonly used with the `<a>` tag).
   ```html
   <a href="https://www.example.com" target="_blank">Open in new tab</a>
   ```

8. **`type`**: Defines the type of an input element (used in forms).
   ```html
   <input type="text" name="username" />
   ```

9. **`placeholder`**: Provides a short hint for text input fields.
   ```html
   <input type="text" placeholder="Enter your name" />
   ```

10. **`value`**: Specifies the value of an input element.
    ```html
    <input type="button" value="Click Me" />
    ```

11. **`width` and `height`**: Specifies the width and height of elements like images.
    ```html
    <img src="image.jpg" width="300" height="200" />
    ```

### **Self-Closing Tags:**
Some HTML tags do not have a closing counterpart and are written as self-closing tags. Common self-closing tags include:
- `<img />` – for embedding images
- `<br />` – for a line break
- `<hr />` – for horizontal rule
- `<input />` – for input fields

### **Example of HTML with Tags and Attributes:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tags and Attributes Example</title>
</head>
<body>
    <h1>Understanding HTML Tags and Attributes</h1>
    <p class="intro" style="color: blue;">This paragraph explains how HTML tags and attributes work.</p>
    <a href="https://www.example.com" target="_blank">Visit Example.com</a>
    <img src="image.jpg" alt="Example Image" width="300" height="200" />
</body>
</html>
```



