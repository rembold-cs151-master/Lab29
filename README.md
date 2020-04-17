# Lab 29: You are Trapped in Here with Me!
##### April 17, 2020
---

Our emphasis today will be on constructing basic classes and interacting with the arcade window, in particular, we want to:
- [ ] Using a class construct a window in which are scene can run
- [ ] Enable basic keyboard control
- [ ] Add some extra drawing that occurs when the mouse is pressed.

The Github repos can be found and added [here]()!

## Instructions
In class we saw how we can bind certain key presses to make our objects do certain movements or cause certain events to happen. Here we'd like to build on that with some constraints, as well as add some mouse interaction.

#### Part A)
Create a new class that inherits from `arcade.Window`. Initialize the class, and set up the basic functionality to draw to the screen a sprite of your choosing in the middle of the screen. You can grab some fun animal sprites from [here](https://willamette.edu/~jjrembold/class_files/cs151/Labs/Images/) again if you want! Make sure that much is working before you go on.

#### Part B)
Add keyboard control so that you can move your sprite about the screen. Setting `.change_x` and `.change_y` on key press or release tends to be more smooth feeling that incrementing `.center_x` or `.center_y` every individual press. Ensure that your sprite can _not_ exit the window! Or in other words, if it was going to run off the window, stop it from doing so. Test to make sure this is functional!

#### Part C)
Add some mouse control so that whenever and wherever you click, a bright laser (line) of some color points from your character sprite to the point on the screen where you clicked. When you stop clicking, the laser should go away.

#### Optional)
Instead of a laser, maybe you can work out how to launch or fire another sprite at the target when you click!


