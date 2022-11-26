# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

### output:

![img01](https://user-images.githubusercontent.com/93427201/204090346-01187885-5950-4067-8002-31ede3da2384.png)

![img02](https://user-images.githubusercontent.com/93427201/204090350-cef98bbd-4767-41fb-b83d-f0b1e01ed014.png)

![img03](https://user-images.githubusercontent.com/93427201/204090358-37daad49-9fca-4d5a-8e09-50a650a8a549.png)

![img04](https://user-images.githubusercontent.com/93427201/204090367-d71501a5-1ac4-4464-8256-6fa4f8c6ecb4.png)

![img05](https://user-images.githubusercontent.com/93427201/204090385-5e39e8a6-64c3-427c-956b-7e896d8a56f8.png)

![img06](https://user-images.githubusercontent.com/93427201/204090394-66cfdb61-771e-414f-9151-c37fb2694408.png)

![img07](https://user-images.githubusercontent.com/93427201/204090402-2017e09b-1551-4286-a63a-f981f7d4e54f.png)

### Robot:
### Linear Interpolation:

![img08](https://user-images.githubusercontent.com/93427201/204090422-0c2d04ff-00ad-4718-bdad-f05261c133ff.png)

### Circular Interpolation:

![img09](https://user-images.githubusercontent.com/93427201/204090437-469e8d51-7c7a-45b0-be86-2c281de20ee3.png)


### Result:
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.





 
