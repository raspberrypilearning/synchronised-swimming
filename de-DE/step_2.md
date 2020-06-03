## Nach links und rechts schwimmen

Beim Synchronschwimmen führt ein Schwimmteam koordinierte Bewegungen zur Musik aus.

Beginnen wir damit, eine Katze schwimmen zu lassen.

--- task ---

Erstelle ein neues Scratch-Projekt.

**Online**: Öffne ein [neues online Scratch-Projekt](http://rpf.io/scratchnew){:target="_blank"}.

**Offline**: Öffne ein neues Projekt im Offline-Editor.

Wenn du den Scratch-Offline-Editor herunterladen und auf deinem Rechner installieren möchtest, findest du die Datei unter diesem Link: [rpf.io/scratchoff](http://rpf.io/scratchoff){:target="_blank"}.

--- /task ---

Lass uns zuerst die Bühne blau machen, damit sie wie ein Schwimmbad aussieht.

--- task ---

Klicke auf "Bühne", dann auf die Registerkarte "Bühnenbilder" und dann auf "In Rastergrafik umwandeln".

![scratch screen with stage, backdrops and convert to bitmap highlighted](images/swim-select-backdrop.png)

--- /task ---

--- task ---

Select a blue colour and the 'Fill with color' tool and then click on the backdrop.

![backdrops tab and fill tool selected](images/swim-fill.png)

--- /task ---

--- task ---

You're going to use a different cat sprite so click on the cross on the walking cat to delete it.

![delete menu selected](images/swim-delete.png)

--- /task ---

--- task ---

Choose the `Cat Flying` sprite from the library and add it to your project.

[[[generic-scratch3-sprite-from-library]]]

![Cat Flying sprite highlighted](images/swim-sprite.png)

The flying cat looks like it could be swimming.

--- /task ---

--- task ---

Now let's get the cat swimming.

Select the 'Cat flying' sprite, click 'Code' and add the code to make the cat rotate left and right when you press the left and right arrow keys.

![swimmer sprite](images/swimmer-sprite.png)

```blocks3
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

```blocks3
when [up arrow v] key pressed
move (10) steps

when [down arrow v] key pressed
move (-10) steps 
```

--- /task ---

--- task ---

Test your code by swimming around the stage using the arrow keys.

--- /task ---
