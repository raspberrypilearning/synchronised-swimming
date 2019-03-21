## Swimming left and right

In synchronised swimming a team of swimmers perform a coordinated routine of moves to music. 

Let's start by getting one cat swimming. 

--- task ---
Open a new Scratch project.

**Online**: open a [new online Scratch project](http://rpf.io/scratchnew){:target="_blank"}.

**Offline**: open a new project in the offline editor.

If you need to download and install the Scratch offline editor, you can find it at [rpf.io/scratchoff](http://rpf.io/scratchoff){:target="_blank"}.

--- /task ---

--- task ---

First let's turn the stage blue so it looks like a swimming pool. 

+ Click on the Stage and then the `Backdrops` Tab. 
+ Choose a blue colour from the palette, click the 'Fill with color' tool and then click on the backdrop. 
	![backdrops tab and fill tool selected](images/swim-fill.png)

--- /task ---

--- task ---

You're going to use a different cat sprite so right-click on the walking cat to delete it. 

![delete menu selected](images/swim-delete.png)

--- /task ---

--- task ---

Choose the `Cat1 Flying` sprite from the library and add it to your project.

[[[generic-scratch-sprite-from-library]]]

![Cat1 Flying sprite highlighted](images/swim-sprite.png)

The flying cat looks like it could be swimming. 

--- /task ---

--- task ---

Now let's get the cat swimming. 

Select the 'Cat1 flying' sprite, click 'Scripts' and add the code to make the cat rotate left and right when you press the left and right arrow keys. 

![swimmer sprite](images/swimmer-sprite.png)

```blocks
when [left arrow v] key pressed
turn ccw (15) degrees

when [right arrow v] key pressed
turn cw (15) degrees
```

--- /task ---

--- task ---

Test your code by pressing the left and right arrow keys on the keyboard.

![cat sprite rotated right](images/swim-right.png)

--- /task ---

--- task ---

And add the code for the forward and backward movement.

![swimmer sprite](images/swimmer-sprite.png)

```blocks
when [up arrow v] key pressed
move (10) steps

when [down arrow v] key pressed
move (-10) steps 
```

--- /task ---

--- task ---

Test your code by swimming around the stage using the arrow keys. 

--- /task ---
