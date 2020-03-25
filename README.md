Collision viewer for Godot Engine
======================================

This is a raycast-based collision viewer, which can be used in the editor to directly visualise collidable surfaces. It is very close to the real colliders than the usual previews, so it can be used to debug said previews.
Brute-forcing that many raycasts can be a bit slow, but results are usually visible after a few seconds.

Installation
--------------

This is a regular editor plugin.
Copy the contents of `addons/zylann.collision_viewer` into the same folder in your project.

To start using it, turn the plugin on in your Project Settings. This will make the 3D view darker, and will start scanning for collidable surfaces.
When you are done inspecting, turn off the plugin.

