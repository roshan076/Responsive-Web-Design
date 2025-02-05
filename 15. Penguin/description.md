# Penguin

## Overview
This project is a simple webpage featuring a penguin character rendered using HTML and CSS. The penguin is animated with basic CSS transitions and a wave animation for the arms. The webpage includes several background elements such as mountains and a sun, giving the impression of an outdoor, animated scene.

## Structure

### HTML
The HTML defines the structure of the page. It contains:

- **Mountains and Sun**: Two mountains (`.left-mountain`, `.back-mountain`) and a sun (`.sun`) create the background scene.
- **Penguin**: The main penguin character is composed of several nested `div` elements that make up different body parts:
  - Penguin's head, face, eyes, and beak.
  - Penguin's body and limbs (arms, legs, feet).
  - Shirt and text with an emoji.
- **Ground**: The ground element creates a backdrop that extends across the bottom of the screen.

### CSS
The CSS provides the styling and animations for the page, including:
- **Background Styling**: Linear gradients for the sky and ground to create a nice background effect.
- **Penguin Styling**: Using `div` elements to build different parts of the penguin, such as:
  - The head, face, eyes, and beak.
  - Body, arms, and feet with specific gradients and shapes.
  - Animation applied to the arms to simulate a waving motion using `@keyframes` and `transform`.
- **Text & Emoji**: A text element with a purple heart emoji and the words "I CSS" to add some playful content to the penguin's shirt.

### Key Features
- **Penguin Animation**: The arms of the penguin animate using CSS keyframes to create a waving motion.
- **Responsive Layout**: The layout is designed to fit across the full screen, using `viewport` units and percentage-based sizing for flexibility.
- **Interactivity**: The penguin can be clicked (scaled up) to create a playful interaction.
- **Gradient Background**: The background uses linear gradients to simulate sky, mountains, and ground with a bright and soft color palette.

## Custom Properties
- `--penguin-face`: Defines the color of the penguin's face.
- `--penguin-picorna`: Defines the color of the penguin's beak and feet.
- `--penguin-skin`: Defines the color of the penguin's skin.

## Animations
- **Wave Animation**: The penguin's left arm moves in a waving motion. The keyframe animation changes the arm's rotation periodically, creating a loop.