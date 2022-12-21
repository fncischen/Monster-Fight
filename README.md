# Monster Fight Snap AR Lens
 SnapAR Monster Fight using Full Body Colliders
 
 ![Monster Fight](./giphy-downsized-large.gif)
 
## Key instructions:

1) We are using Snap Lens Studio's built in world object controller to decide where to place the monster on the AR plane.
2) We are using "Physics Body Colliders" Asset from the Snap Lens Studio asset store which allows us to keep track of real life 3D AR events relative to the colliders set up inside the AR rig. 
![Physics Body Collider Template](./Physics%20Body%20Collider.gif)
3) We use the built in Snap Lens Studio Behavior Scripts are used to check for interactions between physics colliders. In this case the left/right hand physics colliders and the Monster collisions. Each time a "physics collider event" is triggered between the left/right hand and the Monster's body colliders, the monster animation transitions from idle state to monster fall state. 

![Behavior Scripts That Handle Physics Colliders](./Monster-FIght%20Body%20Controller.gif)

4) The monster has built in animations between idle aniamtion state and monster fall state to transition to each time a AR human w/ body collider punches the monster at their colliders. 
