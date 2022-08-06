# About the Project

This is project #1 from CS 440 Computer Graphics, offered at Habib University at Fall 2021. Updated Summer 2022 for refactoring purposes, for a more efficient implementation. Some features have been removed and some will be added. 

There are 5 main features implemented in this project:

1. A height map is used to generate a terrain mesh. A grid, once generated, has it's y-coordinate randomly perturbed, giving the appearance of mountains.
2. A flyby view of the generated terrain is implemented. This is the perspective view obtained from a plane flying at a certain y-coordinate, facing parallel to the ground. The bounds of the view can be dynamically altered within reasonable limits.
3. The terrain is colored such that the 'mountains' have snowy tops, a grassy base, and lakes surrounding them.
4. The pitch, roll, and yaw of the plane is implemented to determine the orientation, within constraints.
5. The terrain is infinite. When the plane approaches the boundary of a patch it is currently flying over, a new patch is dynamically computed and added so the plane never flies out of terrain. 

## Instructions

The HTML file titled 'simulator.html' must be opened in a chromium based browser for the simulation to appear. The browser must also be compatible with WebGL. Control instructions are listed in the simulator.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

