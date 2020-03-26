Collision scanner for Godot Engine
======================================

This is a raycast-based collision viewer, which can be used in the editor to directly visualise collidable surfaces. It is very close to the real colliders compared to the usual previews, so it can be used to debug said previews.
Brute-forcing that many raycasts can be a bit slow, but results are usually visible after a few seconds.

![image](https://user-images.githubusercontent.com/1311555/77599170-cd64bf80-6efb-11ea-9610-7ec6acc28c62.png)
Example of the plugin in action, here showing a heightmap collider.

![image](https://user-images.githubusercontent.com/1311555/77594403-583ebd80-6eee-11ea-8a0a-38b1ce15652f.png)  
A bug with CSGBox, where collision doesn't follow after moving the object.


Installation
--------------

This is a regular editor plugin.
Copy the contents of `addons/zylann.collision_viewer` into the same folder in your project.

To start using it, turn the plugin on in your Project Settings. This will make the 3D view darker, and will start scanning for collidable surfaces.
When you are done inspecting, turn off the plugin.

