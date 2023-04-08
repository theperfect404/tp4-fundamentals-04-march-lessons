## Lesson 5: Combining Animations and Transitions (2 minutes)

In this lesson, we'll discuss when to use animations vs. transitions and how to combine them for enhanced effects. Let's get started!

### When to use animations vs. transitions:

- Use transitions for simple, user-triggered changes in CSS property values over a specified duration.
- Use animations for more complex, reusable, and continuous animations that don't require user interaction to start.

### Combining animations and transitions:

- You can use both animations and transitions on the same element for different purposes or to create more dynamic effects.
- For instance, you can use a transition to change an element's color on hover and an animation to create a pulsating effect continuously.

### Example: Let's create an interactive box that combines animations and transitions:

```html
<div class="box"></div>
```

```css
@keyframes pulse {
  0%,
  100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.1);
  }
}

.box {
  width: 100px;
  height: 100px;
  background-color: blue;
  margin: 50px;
  animation: pulse 2s ease-in-out infinite;
  transition: background-color 0.5s ease-in-out;
}

.box:hover {
  background-color: red;
}
```

In this example, we have a box with a pulsating animation applied to it, while also using a transition to change the background color on hover. The animation plays continuously, and the transition is triggered when the user hovers over the box.

Congratulations! You now understand when to use animations vs. transitions and how to combine them for more dynamic and interactive effects. In the next and final lesson, we'll have a code-along activity where you'll create a simple web page layout and implement animations and transitions to showcase their power. Keep up the excellent work!
