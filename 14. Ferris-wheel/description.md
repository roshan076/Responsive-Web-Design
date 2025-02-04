# Ferris Wheel

## Overview

This project showcases a **Ferris Wheel Animation** created using HTML and CSS. The goal of this animation is to simulate a rotating Ferris wheel with moving cabins. The animation is powered by CSS keyframes, which allow the wheel and the cabins to move continuously in a smooth and visually appealing way.

## Components

### 1. **Wheel**
- The wheel itself is represented by a circular structure created using a `div` with a class of `.wheel`.
- The `border-radius` property is used to make the wheel appear circular.
- The wheel is animated to rotate infinitely using CSS `@keyframes` and the `rotate()` transformation.
- The wheel's rotation speed is controlled by the `animation-duration` property, which is set to 10 seconds for a full rotation.

### 2. **Lines (Spokes)**
- The lines are the spokes of the Ferris wheel. These are represented as `span` elements with a class of `.line`.
- The lines are positioned inside the wheel, radiating from the center using the `position: absolute` and `transform` properties.
- Each line is rotated by different angles (60° increments) to create a spoke-like effect, making them appear to be evenly distributed around the wheel.

### 3. **Cabins**
- The cabins are represented by `div` elements with the class `.cabin`. These are positioned at specific points on the wheel using `position: absolute`.
- The cabins are animated to rotate around the wheel using CSS keyframes. This creates the illusion of the cabins being attached to the rotating wheel.
- The cabins also change colors as they rotate, with the background color transitioning between red, yellow, and purple in the `@keyframes cabins` animation.

### 4. **CSS Animations**
- **Wheel Animation**: The wheel rotates continuously by 360 degrees, creating the effect of a spinning Ferris wheel.
- **Cabin Animation**: Each cabin rotates around its fixed point on the wheel. Additionally, the background color of the cabins changes in a cyclical pattern: starting with red, then changing to yellow and purple at different intervals, adding to the dynamic visual effect.

### 5. **Responsiveness**
- The size of the Ferris wheel is responsive and adjusts based on the viewport width using `vw` (viewport width) units. The maximum size of the wheel is capped at 500px to prevent it from becoming too large on larger screens.

## Features
- **Infinite Rotation**: The Ferris wheel and cabins rotate indefinitely due to the infinite `animation-iteration-count`.
- **Color Changing**: The cabins change color as they rotate, adding an engaging visual effect to the animation.
- **Smooth Transition**: The wheel and cabins have smooth transitions due to the `ease-in-out` timing function applied in the cabin animation.