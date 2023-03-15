# HTML Headings

<ul>
        <li>HTML <b>Headings</b> tag represents the heading of the web page.</li>
        <li>There are 6 <b>Heading</b> tags in HTML Starting from h1 to h6.</li>
        <li>Each <b>Heading</b> tag has different Font sizes (h1 has biggest size and h6 has lowest size).</li>
        <li>Size of each <b>Heading</b> may vary slightly browser to browser.</li>
        <li>Developers can change the <b>Headings</b> style with the help of css.  </li>
</ul>

## Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Html Headings Demo</title>
</head>
<body>
    
    <!-- HTML Headings -->
        <h1>Heading1</h1>
        <hr>
        <h2>Heading2</h2>
        <h3>Heading3</h3>
        <h4>Heading4</h4>
        <h5>Heading5</h5>
        <h6>Heading6</h6>

    <!--Adding Style to Html heading  -->
        <h1 id="heading1" style="font-size: medium; color: brown;">Stylish H1 Heading</h1>
        <script>alert(document.getElementById('heading1').innerText);</script>
</body>
</html>
```

## Output (Exact output you can see by executing above code in your favorite browser)

<img src="https://github.com/kmitsolution/HTML-CSS/blob/main/images/htmlHeading.jpg" height=500 width=500 />
