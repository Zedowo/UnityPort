# UnityPort
Unity Project Import (School)

This is a Engineering project design to use Arduino hardware to stimulate car movement in the Unity Game Engine.
Few Things to Note:
1) This is mainly a prototype designed to show the feasability of such a project. 
    For said emulation, the project uses a ultrasonic sensor and potentiometer to replicate a wheel and pedal. Both use math to aquire the desired value in Unity (i.e 
    Potentiometer uses values between 0-255, which is then scaled to 0-365).
2) Documentation of designs and testing procedures exist in the google drive for the project. This drive is not provided here.
3) Many scripts in the project are unused and for testing purposes only. Same can be said for some of the objects in the game.

In the current state of the project, it can
A) Drive by just moving a ultrasonic sensor, while also adjusting speed.
B) Turn a full 360 degrees by twisting the knob on the potentiometer.
C) Change back and forth (the car is constantly moving in one direction) using the A and S keys.
D) Detect collisions and display said collisions.
