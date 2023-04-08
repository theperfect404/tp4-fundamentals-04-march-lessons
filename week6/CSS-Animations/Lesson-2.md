## Exploring Transition Properties (4 minutes)

In this lesson, we'll explore the various transition properties and provide a simple analogy and example for each. Let's dive in!

### Transition property:

- The transition-property CSS property specifies the name of the CSS property that should be animated when a transition occurs.
- You can use "all" to animate all properties or list specific property names.

### Transition duration:

- The transition-duration CSS property sets the duration of the transition, determining how long it takes for the property values to change.
- The duration is specified in seconds (s) or milliseconds (ms).

### Transition timing function:

- The transition-timing-function CSS property determines the speed curve of the transition, defining how the intermediate property values are calculated.
- Common timing functions include ease, linear, ease-in, ease-out, and ease-in-out.

### Transition delay:

- The transition-delay CSS property defines the amount of time to wait before the transition starts.
- The delay is specified in seconds (s) or milliseconds (ms).

### Simple analogy and example:

- Analogy: Imagine you're on a roller coaster. The transition property is the specific section of the track you're riding. The duration is how long it takes to complete that section. The timing function represents the curves and slopes of the track, and the delay is the waiting time before the ride begins.
- Example: Let's create an interactive box that changes multiple properties with different transition durations and delays:

```html
<div class="box"></div>
```

```css
.box {
  width: 100px;
  height: 100px;
  background-color: blue;
  margin: 50px;
  transition-property: width, background-color;
  transition-duration: 1s, 2s;
  transition-timing-function: ease-in, linear;
  transition-delay: 0s, 1s;
}

.box:hover {
  width: 200px;
  background-color: red;
}
```

In this example, we have a box that changes both its width and background-color on hover. The width transition has a duration of 1s and an ease-in timing function, while the background-color transition has a duration of 2s, a linear timing function, and a 1s delay.

Great job! You've now explored the various transition properties and learned how to use them effectively. In the next lesson, we'll introduce you to CSS animations and keyframes. Keep up the excellent work!

### Codes

- [Lesson 2 Codes](Lesson-2-Examples.html)
