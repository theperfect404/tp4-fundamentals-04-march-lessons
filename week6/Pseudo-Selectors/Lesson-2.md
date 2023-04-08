## Lesson 2: The First Three Selectors (4 minutes)

In this lesson, we'll explore our first three pseudo selectors: `:hover`, `:visited`, and `:first-child`. Let's dive right in!

### `:hover`

- Analogy: The `:hover` pseudo selector is like a chameleon that changes its color when you touch it. When you apply `:hover` to an element, it will change its style when you hover your mouse over it.
- Example: Let's create a button that changes its background color when the mouse is over it:

```css
button:hover {
  background-color: yellow;
}
```

In this example, the button element will change its background color to yellow when you hover your mouse over it.

### `:visited`

- Analogy: The `:visited` pseudo selector is like collecting stamps in a passport after visiting a country. When you click on a link, it's like visiting a new place, and the `:visited` selector helps you keep track of where you've been by changing the style of clicked links.
- Example: Let's change the color of links after they've been clicked:

```css
a:visited {
  color: purple;
}
```

In this example, the link (a) will change its color to purple after you've clicked on it, showing that you've "visited" that link.

### `:first-child`

- Analogy: The `:first-child` pseudo selector is like the oldest sibling who gets a special treat. It allows you to apply a style to the first child element within a parent element.
- Example: Let's style the first item in a list differently from the others:

```css
ul li:first-child {
  font-weight: bold;
}
```

In this example, the first list item (li) within an unordered list (ul) will have a bold font weight, making it stand out from the other items in the list.

Great job! You've now learned about three powerful CSS pseudo selectors: `:hover`, `:visited`, and `:first-child`. In the next lesson, we'll explore more advanced pseudo selectors like `:nth-child`, `:before` & `:after`, and `:not`. Stay tuned!
