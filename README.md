# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-
## Name : SANTHOSH T
## Date : 22-04-2024
## Register Number : 212223220100
## Department : INFORMATION TECHONOLOGY

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 
DART studio screen shots for linear interpolation 
![IMG-20240422-WA0060](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/d0dacc18-1367-4dbd-b3ce-18a1dd9ae343)
![IMG-20240422-WA0064](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/f1e7475c-2efd-4ba0-821e-c5f48f13b6fe)









DART studio screen shots for joint interpolation 

![IMG-20240422-WA0062](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/eef78bbb-df69-4ab3-8a2f-c07e7ffc9348)
![IMG-20240422-WA0063](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/12c3f673-a5a6-48cd-bf18-e78c94399c41)







### Robot movements 

![IMG-20240422-WA0055](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/11550308-534e-4ba7-93ec-a80ee2466d2f)

![IMG-20240422-WA0053](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/b0e133a7-b7d9-4262-a6f2-6897ed443b79)

![IMG-20240422-WA0058](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/30161353-2c58-45c3-b61b-775fb6957f5c)

![IMG-20240422-WA0054](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/eac817b9-5f3e-4a1a-bc80-9b2554595635)

![IMG-20240422-WA0059](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/065d4e0b-08f2-4637-8443-174debb75268)

![IMG-20240422-WA0056](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/1a0f7c35-1dd6-4454-8b8d-fff7ecd4062a)

![IMG-20240422-WA0057](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/17457aed-3530-4a02-a7ab-b048e6370049)

![IMG-20240422-WA0061](https://github.com/SanthoshThiru/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/148958618/874f05ad-e774-45e7-be49-70e27b8d3e1a)






### Results:  
A program is developed for understanding linear and joint interpolation of industrial manipulator and is run sucessfully.
