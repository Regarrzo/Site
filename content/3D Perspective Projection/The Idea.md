## What we want to do
We have a point in 3D space and want to find out where it would end up on our 2D computer screen, given a camera position, direction and field of view.

Mathematically, we have:
- A point $p \in \mathbb{R^3}$
- A camera $C = (C_p, C_d, \theta, d) \in \mathbb{R^3} \times \mathbb{R^3}$ where $C_p$ represents the position and $C_d$ represents the viewing direction, $\theta \in (0, \pi)$ is angle representing the field of view and $d$ is the distance to the image plane.

And we want to find the projection $\bar p \in \mathbb{R^2}$ of the point $p$ onto our screen.

## The camera model
What is a "camera" in this context? Our model looks something like this:

![[camera.svg]] 
