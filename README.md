# penguin

Project Readme: Animated Penguin Illustration
This project features a web-based illustration of an animated penguin, created using HTML for structure and CSS for styling. It demonstrates advanced CSS techniques to render a playful character with interactive elements and simple animation.

Files Overview
index.html
Description: This HTML file defines the structural components of the animated penguin illustration. It includes various div elements nested to form different parts of the penguin (head, body, face, eyes, beak, etc.), as well as environmental elements like mountains, sun, and ground. The file also incorporates a hidden message within the penguin's shirt and an interactive scale effect on click.

Key Features:

Basic HTML5 structure with meta tags for character set and viewport settings.

Links to styles.css to apply the visual design.

Divisions for left-mountain, back-mountain, sun, penguin, and ground to set up the scene.

Detailed div elements within the .penguin container for penguin-head, penguin-body, face (left/right), chin, eye (left/right), eye-lid, blush (left/right), beak (top/bottom), shirt, arm (left/right), and foot (left/right).

A title of "Penguin" for the webpage.

An onclick event on the .penguin that scales it up, indicating an interactive element.

styles.css
Description: This CSS file is responsible for the visual styling, positioning, and animation of the penguin illustration. It uses CSS variables for consistent color management and employs various properties like background, border-radius, transform (skew, rotate, scale), position, and @keyframes to bring the penguin and its environment to life. It also includes an animation for the penguin's left arm.

Key Features:

CSS Variables: Defines custom properties (--penguin-face, --penguin-picorna, --penguin-skin) for easy color adjustments.

Background and Mountains: Styles the body with a linear gradient background and creates detailed mountains using linear-gradient and transform properties for skewing and rotation.

Sun Styling: Defines a circular yellow sun element with absolute positioning.

Penguin Structure: Styles the .penguin container with margin: auto for centering and position: relative, including a transition for the interactive scale effect.

Detailed Penguin Parts: Each part of the penguin (head, face, chin, eyes, beak, body, arms, feet) is meticulously styled with background, border-radius, width, height, and precise top/left/right positioning.

Pseudo-elements: Uses ::before pseudo-element on penguin-body for additional shaping and layering.

Animations: Includes a @keyframes wave animation applied to the .arm.left for a waving motion, demonstrating CSS animation capabilities.

Interactive Scaling: The .penguin:active pseudo-class applies a transform: scale(1.5) and cursor: not-allowed effect when the penguin is clicked, providing user feedback.

Ground Styling: Creates a ground element with a linear gradient background, positioned absolutely.

How to Use
To view the animated penguin illustration, open the index.html file in a web browser. Ensure that the styles.css file is located in the same directory as index.html for the styling and animations to be applied correctly. You can interact with the penguin by clicking on it to see it scale up.

