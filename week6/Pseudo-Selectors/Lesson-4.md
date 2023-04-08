## Lesson 5: Responsive Design with Pseudo Selectors (3 minutes)

In this lesson, we'll show how pseudo selectors can be combined with media queries to create responsive designs that adapt to different screen sizes and devices. Let's get started!

Media queries are a powerful CSS feature that allows you to apply styles based on the characteristics of the user's device or browser, such as screen size or resolution. By combining media queries with pseudo selectors, you can create dynamic, responsive designs that look great on various devices.

Example: Change the style of navigation links when the screen size is below a certain threshold.

First, let's create a simple navigation menu with a few links:

```html
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

Now, let's style the navigation menu using pseudo selectors:

```css
nav ul {
  display: flex;
  list-style-type: none;
}

nav li {
  margin-right: 10px;
}

nav a {
  text-decoration: none;
  color: black;
}

nav a:hover {
  color: blue;
}
```

In this example, we've used the `:hover` pseudo selector to change the color of the links when the user hovers over them.

Finally, let's use a media query to adjust the style of the navigation menu for smaller screens:

```css
@media (max-width: 600px) {
  nav ul {
    display: block;
  }

  nav li {
    margin-bottom: 5px;
  }

  nav a:hover {
    color: red;
  }
}
```

In this example, we've used a media query to apply different styles when the screen width is 600px or smaller. We've changed the layout of the navigation menu, adjusted the margin between the list items, and modified the hover color for the links.

Congratulations! You've now learned how to combine pseudo selectors with media queries to create responsive designs that adapt to different devices and screen sizes. In the next and final lesson, we'll have a code-along activity where you'll apply what you've learned to create a stylish web page using various pseudo selectors. Get ready to put your new skills into practice!
