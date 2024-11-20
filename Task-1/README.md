
# Figma to HTML/CSS Conversion

This project demonstrates converting a Figma design into a functional HTML/CSS webpage. It consists of a navigation bar, a hero section, a features section, and a footer.  

## Files

- **`index.html`**: Contains the structure and layout of the webpage.
- **`style.css`**: Defines the styling for all the elements in the HTML file.

---

## `index.html`

```html
<html>
<head>
    <title>Figma to HTML/CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
        <h1>Welcome to Our Website</h1>
    </header>
    <main>
        <section class="hero">
            <h2>Hero Section</h2>
            <p>main section</p>
            <button>Learn More</button>
        </section>
        <section class="features">
            <h2>Our Features</h2>
            <div class="feature">
                <h3>Feature 1</h3>
                <p>Feature details</p>
            </div>
            <div class="feature">
                <h3>Feature 2</h3>
                <p>Feature details</p>
            </div>
            <div class="feature">
                <h3>Feature 3</h3>
                <p>Feature details</p>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 sai</p>
    </footer>
</body>
</html>
```

### Explanation:

1. **`<html>`**: Defines the root element of the HTML document.
2. **`<head>`**: Contains metadata about the document, like title and links.
3. **`<title>Figma to HTML/CSS</title>`**: Sets the page title shown in the browser tab.
4. **`<link rel="stylesheet" href="style.css">`**: Links the external CSS file for styling.
5. **`<header>`**: Defines the page header, including navigation and a welcome message.
6. **`<nav>`**: Contains the navigation bar with links.
7. **`<ul>` and `<li>`**: Creates a list of navigation links.
8. **`<a href="#">`**: Defines the hyperlink, using `#` as a placeholder for actual links.
9. **`<h1>Welcome to Our Website</h1>`**: Main heading for the page.
10. **`<main>`**: Defines the main content area of the webpage.
11. **`<section class="hero">`**: A section for the hero content (introductory section).
12. **`<button>Learn More</button>`**: Adds a clickable button.
13. **`<section class="features">`**: A section displaying features of the website/product.
14. **`<div class="feature">`**: Individual feature container.
15. **`<footer>`**: Defines the footer containing copyright information.

---

## `style.css`

```css
body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}
```

1. **`font-family`**: Sets the font style to 'Roboto' with fallback to sans-serif.
2. **`margin` and `padding`**: Removes default spacing.
3. **`background-color`**: Sets the background color to light gray.

---

```css
header {
    background-color: #007bff;
    color: #fff;
    padding: 20px;
    text-align: center;
}
```

4. **`background-color`**: Sets the header's background to blue.
5. **`color`**: Changes the text color to white.
6. **`padding`**: Adds space inside the header.
7. **`text-align`**: Centers the header content horizontally.

---

```css
nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}
```

8. **`list-style-type: none;`**: Removes bullet points from the list.
9. **`overflow: hidden;`**: Ensures the navigation content stays within the container.
10. **`background-color: #333;`**: Sets a dark background for the navigation bar.

---

```css
nav li {
    float: left;
}

nav li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

nav li a:hover {
    background-color: #0056b3;
}
```

11. **`float: left;`**: Aligns the list items horizontally.
12. **`display: block;`**: Ensures the anchor tag takes up the full block area.
13. **`padding`**: Adds space inside each link.
14. **`text-decoration: none;`**: Removes the underline from links.
15. **`:hover`**: Adds a hover effect, changing the background color.

---

```css
main {
    padding: 20px;
}

.hero {
    background-color: #f8f9fa;
    padding: 20px;
    text-align: center;
}
```

16. **`main`**: Adds padding around the main content.
17. **`.hero`**: Styles the hero section with a light background and centered text.

---

```css
.features {
    display: block;
    justify-content: space-between;
    flex-wrap: wrap;
}

.feature {
    border: 1px solid #ccc;
    padding: 20px;
    width: 30%;
    margin-bottom: 20px;
    background-color: #fff;
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
}
```

18. **`.features`**: Styles the features section.
19. **`.feature`**: Defines individual feature boxes with a border, shadow, and padding.

---

```css
.feature h3 {
    color: #007bff;
}

.feature p {
    color: #6c757d;
}

.feature:hover {
    background-color: #f2f2f2;
    transform: scale(1.02);
    transition: all 0.3s ease-in-out;
}
```

20. **`.feature:hover`**: Adds a hover effect with scaling and background color change.

---

```css
footer {
    text-align: center;
    padding: 10px;
    background-color: #dc3545;
    color: #fff;
}
```

21. **`footer`**: Styles the footer with a red background and white text.

