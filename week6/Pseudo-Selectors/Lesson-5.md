## Lesson 5: Code-Along Activity (4 minutes)

In this code-along activity, we'll create a simple web page layout with various elements (headings, paragraphs, lists, and buttons). We'll showcase the power of pseudo selectors by styling the page using the different selectors taught in the course. Let's get started!

### First, create the HTML structure with some example content:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lesson 5 Practice Project</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>My Pseudo Selectors Adventure</h1>
    <p>Once upon a time, in a world of CSS...</p>

    <h2>Chapter List</h2>
    <ul>
      <li>
        <a
          href="https://theperfect404.github.io/tp4-fundamentals-04-march-lessons/week6/Pseudo-Selectors/Lesson-1.html"
          target="_blank"
          >Introduction</a
        >
      </li>
      <li>
        <a
          href="https://theperfect404.github.io/tp4-fundamentals-04-march-lessons/week6/Pseudo-Selectors/Lesson-2.html"
          target="_blank"
          >The First Three Selectors</a
        >
      </li>
      <li>
        <a
          href="https://theperfect404.github.io/tp4-fundamentals-04-march-lessons/week6/Pseudo-Selectors/Lesson-3.html"
          target="_blank"
          >Advanced Pseudo Selectors</a
        >
      </li>
      <li>
        <a
          href="https://theperfect404.github.io/tp4-fundamentals-04-march-lessons/week6/Pseudo-Selectors/Lesson-4.html"
          target="_blank"
          >Responsive Design with Pseudo Selectors</a
        >
      </li>
    </ul>

    <h2>Join the Adventure</h2>
    <button>Start Now</button>
  </body>
</html>
```

### Next, create a CSS file (styles.css) to style the web page using various pseudo selectors:

```css
body {
  font-family: Arial, sans-serif;
}

h1:before,
h1:after {
  content: "✧";
  margin: 0 5px;
}

p:first-line {
  font-weight: bold;
  color: blue;
}

a:hover {
  color: darkblue;
}

a:visited {
  color: gray;
}

ul {
  list-style-type: none;
}

ul li:first-child {
  font-weight: bold;
}

ul li:nth-child(2n) {
  background-color: lightblue;
}

button {
  background-color: cornflowerblue;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}

button:hover {
  background-color: darkblue;
}
```

In this example, we've applied various pseudo selectors:

- `:before` and `:after` on the h1 heading to add decorations.
- `:first-line` on the paragraph to style the first line.
- `:first-child` and `:nth-child` on the list items to style the first item and every second item.
- `:hover` on the button to change its background color on mouse hover.

### Save both the HTML and CSS files and open the HTML file in your browser to see the result.

Congratulations! You've successfully completed the code-along activity and applied various pseudo selectors to style a web page. By now, you should have a good understanding of how to use pseudo selectors to create dynamic and engaging web designs.

We hope you enjoyed this short course. Keep practicing and exploring the world of CSS, and soon you'll be able to create amazing web designs with ease. Good luck on your future projects!
