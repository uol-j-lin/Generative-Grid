# Evolving Generative Grid
* The background colors are lerped based on their RGB components
* The colors change organically over time on a 25 x 25 compass grid
* The compass angle is determine based on a 3D noise value generated by its XY coordinates and the frame count
* The mouse's horizontal position determines the rate of rotation (based on Perlin noise) of the compasses and the rate of color change
* The compass length and color becomes more chaotic as the mouse cursor moves left

Live Demo: [https://evolving-generative-grid.netlify.app/](https://evolving-generative-grid.netlify.app/)

[<img width="765" alt="image" src="https://user-images.githubusercontent.com/114364831/209480761-50b7edc7-1e44-42e2-ad7c-5d49eced2c51.png">](https://evolving-generative-grid.netlify.app/)
