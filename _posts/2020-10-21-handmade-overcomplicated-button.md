---
layout: post
title: Robot - How I ended up overcomplicating a button
---

If you are trying to put together your own robot following [my instructions](https://github.com/angelalonso/robot) you might have stepped into a photo interrupter being used as a simple button.

Here's the reason behind that:

For v2 I wanted to add some kind of input and output.

For now, the bare minimum input I needed was a button, and I had a bunch of [these sensors](https://www.banggood.com/Geekcreit-37-In-1-Sensor-Module-Board-Set-Starter-Kits-SENSOR-KIT-For-Arduino-Carton-Box-Package-p-89734.html?akmClientCountry=DE&&cur_warehouse=CN) in a box somewhere.

My first try was the [metal touch sensor](https://steemit.com/utopian-io/@ted7/arduino-101-using-a-ky-036-metal-touch-sensor). Never got to make it work, and I gave it a 50% chance that the sensor was broken (the integrated LED turned on and off for a couple times, then stopped reacting to any touch).

![metal touch sensor mounted](/assets/robot/metal_touch_mounted.jpg) ![metal touch construct](/assets/robot/metal_touch_construct.jpg)  
*This is what I put together with the metal touch sensor*

Then I moved to the most obvious one: the [button sensor](https://steemit.com/utopian-io/@ted7/arduino-101-using-a-ky-036-metal-touch-sensor). Also didn't work.

At this point I was frustrated and tired. I wanted to have something working that would return a 0 or 1 to the robot's [brain program](https://github.com/angelalonso/robot/tree/master/brain).

So I connected the photo interrupter sensor, put a plastic card in the hole and...bingo! 0s and 1s flowing in my logs!


I had to figure out how to make a button out of that simple mechanism, and came up with a tunnelled stick and a rubber band.

![wooden button_above](/assets/robot/wooden_button_above.jpg) ![wooden button mounted](/assets/robot/wooden_button_mounted.jpg)  

![wooden button_side](/assets/robot/wooden_button_side.jpg) ![wooden button side_pressed](/assets/robot/wooden_button_side_pressed.jpg)  
*If it works, it works*

I hope it makes more sense now.  
