# Monster Fight
 SnapAR Monster Fight using Full Body Colliders
 
 ![Monster Fight](https://i.giphy.com/media/j0FAO0Os3uDjUh1A2b/giphy-downsized-large.gif)
 
## Key instructions:

1) We are using Snap Lens Studio's built in world object controller to decide where to place the monster on the AR plane.
2) We are using "Physics Body Colliders" Asset from the Snap Lens Studio asset store which allows us to keep track of real life 3D AR events relative to the colliders set up inside the AR rig. 
3) We use the built in Snap Lens Studio Behavior Scripts are used to check for interactions between physics colliders. In this case the left/right hand physics colliders and the Monster collisions. Each time a "physics collider event" is triggered between the left/right hand and the Monster's body colliders, the monster animation transitions from idle state to monster fall state. 
4) The monster has built in animations between idle aniamtion state and monster fall state. 
