## Create the team

Synchronised swimming needs more than one cat! We can use `create clone of`{:class="block3control"} to create copies that behave in the same way.

--- task ---

First let's add code to make sure the cat always starts in the same position when you click the green flag.

![swimmer sprite](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

Test your code by pressing some arrow keys and then clicking the green flag to return to the start position.

--- /task ---

--- task ---

Now we can use a `repeat`{:class="block3control"} loop to create 6 clones (copies) of the cat.

![水上精靈貓](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

Loops are used to do the same thing multiple times.

--- /task ---

--- task ---

You don't want all the cats to be in the same position!

Add code to rotate 60 degrees before creating each clone.

![水上精靈貓](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
repeat (6)
+turn cw (60) degrees
create clone of (myself v)
end
```

--- /task ---

--- task ---

 使用方向鍵來測試你寫好的程式。 你應該能夠創建一些驚艷的水上芭蕾表演了！

![6 cat sprites all in different positions and rotations](images/swim-test-clones.png)

--- /task ---
