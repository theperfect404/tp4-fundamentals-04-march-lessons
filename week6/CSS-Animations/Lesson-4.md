## Lesson 4: Exploring Animation Properties (4 minutes)

In this lesson, we'll explore various animation properties in more detail and provide a simple analogy and example for each. Let's dive in!

### Animation name:

- The animation-name CSS property specifies the name of the @keyframes rule that defines the animation.
- You can apply multiple animations to an element by listing multiple animation names separated by commas.

### Animation duration:

- The animation-duration CSS property sets the length of time it takes for the animation to complete one cycle.
- The duration is specified in seconds (s) or milliseconds (ms).

### Animation timing function:

- The animation-timing-function CSS property determines the speed curve of the animation, defining how the intermediate property values are calculated.
- Common timing functions include ease, linear, ease-in, ease-out, and ease-in-out.

### Animation delay:

- The animation-delay CSS property defines the amount of time to wait before the animation starts.
- The delay is specified in seconds (s) or milliseconds (ms).

### Animation iteration count:

- The animation-iteration-count CSS property specifies how many times the animation should repeat.
- You can use "infinite" to make the animation loop indefinitely.

### Animation direction:

- The animation-direction CSS property determines the direction in which the animation plays.
- Common values include "normal", "reverse", "alternate", and "alternate-reverse".

### Animation fill mode:

- The animation-fill-mode CSS property specifies how the animation should apply styles to the target element before and after the animation has finished.
- Common values include "none", "forwards", "backwards", and "both".

### Animation play state:

- The animation-play-state CSS property determines whether the animation is running or paused.
- Common values include "running" and "paused".

### Simple analogy and example:

- Analogy: Imagine a dancer performing a choreographed routine. The animation name is the title of the routine, the duration is the length of the performance, the timing function represents the rhythm of the dance, and the delay is the waiting time before the dancer starts. The iteration count indicates how many times the dancer repeats the routine, the direction represents the dancer's movements, the fill mode determines the dancer's starting and ending poses, and the play state indicates whether the dancer is performing or taking a break.
- Example: Let's create a spinning and pulsating circle animation:

```html
<div class="circle"></div>
```

```css
@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

@keyframes pulse {
  0%,
  100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.2);
  }
}

.circle {
  width: 50px;
  height: 50px;
  background-color: blue;
  border-radius: 50%;
  animation: spin 5s linear infinite, pulse 2s ease-in-out infinite;
}
```

In this example, we've created two @keyframes rules, "spin" and "pulse". The "spin" rule rotates the circle, while the "pulse" rule scales the circle. We apply both animations to the circle element by listing their names, durations, timing functions, and iteration counts Great job!

### Codes

- [Lesson 4 Codes](Lesson-4-Examples.html)
