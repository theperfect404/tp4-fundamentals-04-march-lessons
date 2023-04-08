## Lesson 1: Understanding Transitions (4 minutes)

In this lesson, we'll introduce you to transitions, discuss properties and timing, and provide a simple analogy and example. Let's get started!

### Introduction to transitions:

- Transitions enable you to create smooth and gradual changes in CSS property values over a specified duration.
- Transitions are triggered by user interactions, like hovering over an element or clicking on a button.

### Properties and timing:

- You can control the transition's properties, such as which CSS property to transition, the duration of the transition, and the timing function.
- Timing functions define how the intermediate property values are calculated during the transition, creating different easing effects.

### Simple analogy and example:

- Analogy: CSS transitions are like a sliding door that smoothly opens or closes when you push or pull it. The door's motion depends on the force and speed you apply.
- Example: Let's create a smooth background color change on a button when a user hovers over it:

```html
<button>Click me!</button>
```

```css
button {
  background-color: blue;
  color: white;
  padding: 10px 20px;
  cursor: pointer;
  transition: background-color 0.5s ease-in-out;
}

button:hover {
  background-color: red;
}
```

In this example, we've added a transition property to the button element. The transition applies to the background-color, has a duration of 0.5 seconds, and uses the ease-in-out timing function for a smooth effect. When the user hovers over the button, the background color changes from blue to red.

Congratulations! You now have a basic understanding of CSS transitions, their properties, and timing. In the next lesson, we'll delve deeper into transition properties and how to use them effectively. Keep up the great work!

### Codes

- [Lesson 1 Codes](Lesson-1-Examples.html)
