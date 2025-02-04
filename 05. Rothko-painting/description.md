# Rothko Painting

This project is a visual representation of a Rothko-style painting using HTML and CSS. The design features overlapping colored blocks within a frame, mimicking the abstract art style of Mark Rothko.

## Overview

The artwork consists of a rectangular canvas framed with a solid black border. The canvas contains three colored blocks of varying sizes and shades that overlap slightly, creating an abstract yet harmonious design. The design incorporates various techniques like blur effects, rotations, box shadows, and rounded corners to capture the essence of Rothko's layered and atmospheric style.

### Structure

- **Frame**: A large border surrounds the canvas, giving it a formal, finished appearance.
- **Canvas**: A rectangular background where the colored blocks are placed. The canvas is slightly blurred to add an artistic, abstract touch.
- **Colored Blocks**: 
  - **Block One**: A yellowish block that is positioned slightly off-center and has a slight rotation.
  - **Block Two**: A red block placed below the first block with a small rotation and rounded edges.
  - **Block Three**: A deeper red block positioned at the bottom with a significant rotation and soft edges.

## CSS Styling

The painting is styled with CSS using various properties to create the appearance of abstract art:
- **Frame**: The frame has a black border with padding and margins, positioning the canvas in the center of the page.
- **Canvas**: The background of the canvas is a deep red (`#4d0f00`), and the canvas has a slight blur effect to make the painting appear soft and atmospheric.
- **Blocks**:
  - Each block (`.one`, `.two`, `.three`) has a different color and size, with slight rotations to break up the symmetry and add depth.
  - The blocks have `box-shadow` and `border-radius` properties to create shadows and rounded corners for a soft, painted effect.
  - The `filter: blur` property is used on both the canvas and blocks to simulate the misty, dreamlike quality often seen in Rothko’s paintings.

## Features

- **Layered Effect**: The overlapping blocks, combined with the blur effects, create a sense of depth and layering.
- **Abstract Composition**: The random rotation of blocks and varying sizes gives the form an abstract, artistic touch similar to Rothko's style.
- **Atmosphere**: The use of `filter: blur` enhances the overall visual feel, giving the impression of a softened, glowing painting.

