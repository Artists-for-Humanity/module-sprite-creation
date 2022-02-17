# Building Sprite Sheets
A sprite is a two-dimensional bitmap that is integrated into a larger scene, most often in a 2D video game.  
Sprite sheets are comprised of several sprites in a single image file.  
JPEG and PNG are both common bitmap file types.

## Why Use Sprite Sheets?
One major reason to use sprite sheets is for memory's sake.
One file containing all images would take up less memory than if all images were their own files.  
It also makes organization simpler, since your are dealing with less clutter, and sprites will ideally be logically grouped.

### Logical Grouping?
When we say "logically grouped," we mean to say that sprite sheets will contain all assets needed for a specific object or setting.  
For example, you may "logically group" all platform or ground tile sprites in one sprite sheet.  
You may also group all  prop or weapon sprites in a single sheet.  
However, this method of grouping is possibly most useful for storing sprite animations.

## Animations
### What is an animation?  
Simply put, an animation is a series of unique images shown sequentially to give the illusion of motion.  
Sprite sheets are great for storing animation, since each frame of the animation can be stored as a sprite in a single sheet.  
You can have a sprite sheet for a character's run cycle.  
Or you could have the sprite sheet for an attack animation.  
You could even theoretically have a sprite sheet containing a character's full range of motion.  

### Here's an example of a simple sprite sheet:  
  

![This little guy can't be stopped!](images/alien-sheet.png)

It only contains frames for standing, jumping and running, but you can see how each sprite is a frame of an animation.

## What We'll Need
In this tutorial, we're going to walk through how this sheet was made, with the hopes of you understanding how to make your own by the end.  
We're going to use the following software to accomplish this:  
* Adobe Photoshop
* Adobe Animate

# Let's Begin!
If you're ready to start, you can move on to [step 1](tutorial/step1.md).