# Various Visualizations for Germany Using Boundary Masks

This project explores different techniques to create unique visualizations constrained by the boundary mask of Germany.

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">

<div style="flex: 1; padding-right: 20px;">
<h2>1. Animated 2D Gaussian Visualization</h2>
<p>Dynamic 2D Gaussian functions (bell curves) are displayed within the borders of a mask based on a black-and-white representation of Germany. The Gaussians change their position, width, and amplitude randomly over time, resulting in a vivid, evolving animation. Areas outside the mask are excluded, and the animation is saved as a <code>.gif</code>.</p>
</div>

<div style="flex: 1;">
<img src="gifs/germany_animation_masked_100x100.gif" alt="Animated Gaussian Visualization" style="max-width: 100%;">
</div>

</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">

<div style="flex: 1; padding-right: 20px;">
<h2>2. Filling a Mask with Circles</h2>
<p>This visualization fills the shape of Germany with randomly placed colorful circles of fixed size. The circles are positioned within the black areas of the mask without overlapping, creating an aesthetically pleasing result. A predefined color palette enhances the visual effect, and the output is saved as an image.</p>
</div>

<div style="flex: 1;">
<img src="images/germany_circles.png" alt="Filling Mask with Circles" style="max-width: 100%;">
</div>

</div>
