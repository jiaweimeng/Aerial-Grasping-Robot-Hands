# Aerial-Grasping-Robot-Hands
## Introduction
Over the last decade, a new class of adaptive robot hands has been proposed that facilitates the execution of stable grasps in unstructured environments even when the object properties are not known. This attribute of adaptive hands is due to the under-actuation and their mechanical compliance that allow them to conform to the object surface. 

This adaptive robot hand is designed for UAV-based autonomous package delivery problem. Therefore, the robot hand must be extremely quick (< 100 ms), [lightweight](https://github.com/newdexterity/Aerial-Grasping-Robot-Hands/blob/master/Media/weight_analysis_aerial_gripper.pdf) (< 505 g), provide reliable grasping and enable perching for aerial platforms such as UAVs.

## Prototype
The prototype of this aerial grasping robot hand is designed by [New Dexterity Research Team](https://www.newdexterity.org/) from the University of Auckland.

<p align="center">
  <img width="280" height="280" src="https://github.com/newdexterity/Aerial-Grasping-Robot-Hands/blob/master/Media/prototype.png">
</p>

<p align="center"> 
  Figure 1. Prototype of the aerial grasping robot hand
</p>

## Quick release mechanism
A novel quick release mechanism which contains two servomotors has been proposed in this paper. The quick release mechanism allows the main servomotor to winch the tendons and open each finger. When the other servomotor is actuated, the dog collar disengages with the 35T spur gear, allowing the dog collar and the drum to rotate freely.

<p align="center">
  <img width="600" height="300" src="https://github.com/newdexterity/Aerial-Grasping-Robot-Hands/blob/master/Media/quick_release_mechanism.png">
</p>

<p align="center"> 
  Figure 2. Quick release mechanism
</p>                                           

## Sensors
* [Infrared sensor](http://www.sharp-world.com/products/device/lineup/data/pdf/datasheet/gp2y0a21yk_e.pdf)

## Contents
In this repository you can find:
* CAD files of an ultra-fast aerial grasping robot hand
* Archive of prototype images
* Arduino code for controling this robot hand

## Notes
Please open a [Github issue](https://github.com/newdexterity/Aerial-Grasping-Robot-Hands/issues) if you encounter any problem.
