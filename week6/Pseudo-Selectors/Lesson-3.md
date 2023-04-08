## Lesson 3: Advanced Pseudo Selectors (4 minutes)

In this lesson, we'll explore more advanced pseudo selectors: `:nth-child`, `:before` & `:after`, and `:not`. Let's get started!

### `:nth-child`

- Analogy: The `:nth-child` pseudo selector is like selecting a book (`:nth-child`) on a bookshelf. It allows you to apply a style to selected element within a parent element, just like choosing a book on the shelf to give it a special bookmark or decoration.
- Example: Let's style every third item in a list differently:

```css
li:nth-child(3) {
  background-color: lightblue;
}
```

In this example, every third item in lists (li) will have a light blue background color, creating a visually appealing pattern.

### `:before` & `:after`

- Analogy: The `:before` and `:after` pseudo selectors are like adding a frame around a painting. They allow you to insert extra content or decorations before or after an element without altering the HTML code, just like positioning a frame around a painting to enhance its presentation without modifying the artwork itself.
- Example: Let's add a decoration before and after a heading:

```css
h2:before,
h2:after {
  content: "✧";
  margin: 0 5px;
}
```

In this example, we add a sparkle symbol (✧) before and after each h2 heading. The content property is used to specify the decoration, and the margin property adds some spacing.

### `:not`

- Analogy: The `:not` pseudo selector is like choosing all but one type of candy in a candy store. It allows you to select all elements that do not match a certain condition or selector.
- Example: Let's select all input fields except for the ones with a specific class:

```css
input:not(.no-style) {
  border: 2px solid blue;
}
```

In this example, all input elements without the "no-style" class will have a 2px solid blue border.

Congratulations! You've now learned about more advanced CSS pseudo selectors: `:nth-child`, `:before`, `:after`, and `:not`. In the next lesson, we'll discuss how to use pseudo selectors for responsive design with media queries. Stay tuned!
