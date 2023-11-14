# leo_common 

Common ROS packages for Leo Rover that will work no matter on what machine they were run in the ROS network. Usable for both the real robot operation and the simulation.

* [leo] - Metapackage for this repository.
* [leo_description] - Robot description (URDF model).
* [leo_msgs] - Message and Service definitions.
* [leo_teleop] - Scripts for robot's teleoperation.

Visit each package's ROS Wiki page for more information. \
For more information about the robot, visit [Robots/Leo Rover].

[leo]: http://wiki.ros.org/leo
[leo_description]: http://wiki.ros.org/leo_description
[leo_msgs]: http://wiki.ros.org/leo_msgs
[leo_teleop]: http://wiki.ros.org/leo_teleop
[Robots/Leo Rover]: http://wiki.ros.org/Robots/Leo%20Rover

## Copy right notes for components from third parties

### Parts from Leo Rover
The files `leorover_description/models/model_extensions/xavier_mount.dae` and `leo_description/models/model_extensions/long_camera_mast.dae` have been taken respectively derived from the CAD model from the Leo Rover. To get the CAD model, see [https://www.leorover.tech](https://www.leorover.tech/documentation/specification).


### Parts from Intel RealSense
The file `realsense_d455.dae` from has been taken from the CAD model repositories of the website of [Intel RealSense](https://dev.intelrealsense.com/docs/stereo-depth-camera-d400)

### Parts for the battery mount
The mount for the makita battery has been taken from [ThingyVerse](https://www.thingiverse.com/thing:1857196) with the following notes:

- LICENSE.txt: This thing was created by Thingiverse user Henk_i3, and is licensed under Creative Commons - Attribution
- README.txt: Makita Battery Model with mounting screws by Henk_i3 on Thingiverse: https://www.thingiverse.com/thing:1857196