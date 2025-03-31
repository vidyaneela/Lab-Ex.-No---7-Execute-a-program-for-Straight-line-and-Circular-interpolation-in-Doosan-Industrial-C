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

## Program:

![image](https://user-images.githubusercontent.com/75413726/206198383-0a55a5d0-ab31-4d18-947b-8724a309b9ec.png)
![image](https://user-images.githubusercontent.com/75413726/206198411-fbf9ecf6-1570-4c17-91df-2dde9ecee6f0.png)
![image](https://user-images.githubusercontent.com/75413726/206198452-8aa0f677-8187-4ab4-b774-629bc5bfc1df.png)
![image](https://user-images.githubusercontent.com/75413726/206198499-c2791b4a-78e9-4e57-bee6-c75ea6f5e1a1.png)
![image](https://user-images.githubusercontent.com/75413726/206198515-fe909bb4-38fa-4544-932d-1c4fcfd59862.png)

### Linear Interpolation

![image](https://user-images.githubusercontent.com/75413726/206198563-aae901aa-df9c-4ebe-a537-d441efbf922f.png)

### Circular Interpolation

![image](https://user-images.githubusercontent.com/75413726/206198619-93b083c0-c7ed-4c83-997d-3071ba742c4c.png)

### output

### Linear Interpolation

![image](https://user-images.githubusercontent.com/75413726/206198662-b49c14f6-bb46-4e48-84e8-d8d356a5f94a.png)

### Circular Interpolation

![image](https://user-images.githubusercontent.com/75413726/206198760-c8cc237e-65fe-4710-b817-6dc1481f08c2.png)


### Results 

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.

 
