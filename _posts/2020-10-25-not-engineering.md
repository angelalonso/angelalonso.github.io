---
layout: post
title: Robot - What happens when you don't do the math
---

So I had this problem: the robot doesn't move straight.  
I doesn't matter if I put more power on one of the motors or the other, it slightly goes to one side, sort of randomly.

The reason? the chassis for the robot includes a third wheel that also rotates on the vertical axis to follow movement produced by the two motors.

![rear axle with one wheel](/assets/robot/bottom.jpg)

The position the wheel starts from affects where the robot goes when it moves forward or backward (that's the "sort of" in "sort of randomly").

So I thought of putting two wheels that only rotate as they should, and get rid of that random wheel it has. The donor was a suitcase's wheelbase that I found...somewhere.

![rear axle with two wheels](/assets/robot/rear_axle_test.jpg)

Put together some support with wire, mounted it and... robot goes straight!

![robot goes straight](/assets/robot/rear_axle_2wheel_test.gif)

Yeaaaaahwait! what if the robot wants to rotate? Bummer, the robot doesn't rotate because the rubber  on the new wheels don't go well with slipping sideways.

And that is a good example of why engineering is so much more than having ideas that "might work".

When you don't do the math, you waste time putting something awesome together that you have to get rid of.
