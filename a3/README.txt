Michael Wang
804862406

Added a refractive sphere. Fairly simple.

Added a moon. Involved creatinig a new skybox in order to map the texture.

Added a grass plane. Made the Reflective and Refractive spheres show the grass texture instead of the floor of the skybox.

Added two armadillos. They are playing a nice game of catch with the refractive sphere.
Making the ball bounce back and forth required defining a clock and an update function. The y position is based on a sin funtion while the z position is updated based on a piecewise function (it probably would have been better to define y using a quadratic function. Oh well).