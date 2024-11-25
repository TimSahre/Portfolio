# Various Visualizations for Germany Using Boundary Masks [<img src="images/germany_resized_100x100_rgba.png" alt="Used Mask" style="width: 3%;">]

This project explores different techniques to create unique visualizations constrained by the boundary mask of Germany.

[View Notebook](https://colab.research.google.com/drive/1cTRV19aWN1l-nwperGx57SVPyF0c7LoV)

| Description | Visualization |
|------|---------------|
| **1. Animated 2D Gaussian Visualization**  <br> Dynamic 2D Gaussian functions (bell curves) are displayed within the borders of a mask based on a black-and-white representation of Germany. The Gaussians change their position, width, and amplitude randomly over time, resulting in a vivid, evolving animation. Areas outside the mask are excluded, and the animation is saved as a `.gif`. | ![Animated Gaussian Visualization](gifs/germany_animation_masked_100x100.gif) |
| **2. Filling a Mask with Circles**  <br> This visualization fills the shape of Germany with randomly placed colorful circles of fixed size. The circles are positioned within the black areas of the mask without overlapping, creating an aesthetically pleasing result. A predefined color palette enhances the visual effect, and the output is saved as an image. | ![Filling Mask with Circles](images/germany_circles.png) |
| **3. Elevation Line Visualization**  <br> This visualization uses a topographic elevation dataset for Germany, downscaled and masked to match the boundary of the country. Lines are drawn horizontally to represent different rows of elevation data, with a vertical offset applied to create a layered effect. Every fifth line is displayed in white, while others are excluded, resulting in a stylized, clean visualization. The output is saved as an image. | ![Elevation Line Visualization](images/terrain_germany.png) |
