### Lesson 6: Code-Along Activity (6 minutes)

In this lesson, we'll have a code-along activity where you'll create a simple web page layout and implement animations and transitions to showcase their power. Let's get started!

### Create a simple web page layout:

- For this activity, we'll create a web page with a header, a navigation bar, and three boxes that represent content sections.

```html
<header>
  <h1>Animated Web Page</h1>
</header>
<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>
<div class="container">
  <div class="box">1</div>
  <div class="box">2</div>
  <div class="box">3</div>
</div>
```

```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: blue;
  color: white;
  text-align: center;
  padding: 20px;
}

nav {
  display: flex;
  justify-content: center;
  background-color: darkblue;
  padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
}

.container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  padding: 20px;
}

.box {
  width: 100px;
  height: 100px;
  background-color: lightblue;
  margin: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 24px;
  color: white;
}
```

### Implement transitions:

- Let's add a transition to the navigation links so that their background color changes smoothly when a user hovers over them.

```css
nav a {
  /* Add the following line */
  transition: background-color 0.3s ease-in-out;
}

nav a:hover {
  background-color: rgba(255, 255, 255, 0.1);
}
```

### Implement animations:

Now, let's add a pulsating animation to the content boxes.

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
  /* Add the following line */
  animation: pulse 2s ease-in-out infinite;
}
```

Great job! You've now created a simple web page layout and implemented animations and transitions to showcase their power. You've completed the "CSS Animations and Transitions: A 20-Minute Journey into the World of Web Motion" course. Congratulations, and keep experimenting with different animations and transitions to create more interactive and dynamic web experiences!

### Codes

- [Lesson 6 Codes](Lesson-6-Examples.html)
