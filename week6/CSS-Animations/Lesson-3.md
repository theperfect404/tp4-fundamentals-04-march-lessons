## Lesson 3: Understanding Animations (4 minutes)

In this lesson, we'll introduce you to CSS animations, discuss keyframes, and explore animation properties. We'll also provide a simple analogy and example. Let's get started!

### Introduction to animations:

- CSS animations allow you to create complex and reusable animations by defining multiple keyframes.
- Unlike transitions, animations can be continuous and do not require user interaction to start.

### Keyframes:

- Keyframes are used to specify the behavior of the animation at different points in time.
- The @keyframes rule defines the intermediate property values between the start and end of the animation.

### Animation properties:

- You can control various aspects of an animation, such as its name, duration, timing function, and delay, as well as its iteration count, direction, fill mode, and play state.

### Simple analogy and example:

- Analogy: CSS animations are like a flipbook, where each page represents a keyframe. As you flip through the pages, the images create the illusion of motion.
- Example: Let's create a simple animation that moves a box from left to right:

```html
<div class="box"></div>
```

```css
@keyframes move {
  0% {
    left: 0;
  }
  100% {
    left: 100px;
  }
}

.box {
  width: 50px;
  height: 50px;
  background-color: blue;
  position: absolute;
  animation-name: move;
  animation-duration: 2s;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}
```

In this example, we've created a keyframes rule named "move" that defines the starting and ending positions of the box. We then apply the animation to the box element by specifying its name, duration, timing function, and iteration count.

Congratulations! You now have a basic understanding of CSS animations, keyframes, and animation properties. In the next lesson, we'll explore each animation property in more detail. Keep up the great work!

### Codes

- [Lesson 3 Codes](Lesson-3-Examples.html)
