# Landing_page-Creating a landing page for a recipe using HTML, CSS, and JavaScript involves several steps. Here's a simple example to get you started.

### HTML (index.html)
This file contains the structure of your webpage.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Recipe</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Delicious Chocolate Cake</h1>
        <nav>
            <ul>
                <li><a href="#ingredients">Ingredients</a></li>
                <li><a href="#instructions">Instructions</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <img src="chocolate-cake.jpg" alt="Chocolate Cake">
        </section>

        <section id="ingredients">
            <h2>Ingredients</h2>
            <ul>
                <li>1 cup sugar</li>
                <li>1/2 cup butter</li>
                <li>2 eggs</li>
                <li>1 cup flour</li>
                <li>1/2 cup cocoa powder</li>
                <li>1 tsp baking powder</li>
                <li>1/2 tsp salt</li>
                <li>1 cup milk</li>
            </ul>
        </section>

        <section id="instructions">
            <h2>Instructions</h2>
            <ol>
                <li>Preheat the oven to 350°F (175°C).</li>
                <li>Cream together the sugar and butter.</li>
                <li>Beat in the eggs, one at a time.</li>
                <li>Mix in the flour, cocoa powder, baking powder, and salt.</li>
                <li>Stir in the milk until the batter is smooth.</li>
                <li>Pour into a greased baking pan.</li>
                <li>Bake for 30-35 minutes or until a toothpick comes out clean.</li>
                <li>Let cool before serving.</li>
            </ol>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Delicious Recipes. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```

### CSS (styles.css)
This file contains the styles for your webpage.

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

#hero {
    text-align: center;
    margin: 20px 0;
}

#hero img {
    max-width: 100%;
    height: auto;
}

main {
    padding: 20px;
}

h2 {
    color: #333;
    border-bottom: 2px solid #333;
    padding-bottom: 5px;
}

ul, ol {
    padding-left: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```

### JavaScript (script.js)
This file can contain any interactive elements or additional functionalities for your webpage.

```javascript
document.addEventListener('DOMContentLoaded', () => {
    // Add any JavaScript you need here
});
```

### Images
You should have an image named `chocolate-cake.jpg` in the same directory as your HTML, CSS, and JavaScript files, or adjust the image path accordingly.

### File Structure
Your project structure should look something like this:
```
/your-project-directory
    ├── index.html
    ├── styles.css
    ├── script.js
    └── chocolate-cake.jpg
```

This simple example sets up a basic landing page for a chocolate cake recipe, including a header, navigation, hero image, ingredients, instructions, and a footer. You can expand on this by adding more styles, animations, and interactive elements as needed.
