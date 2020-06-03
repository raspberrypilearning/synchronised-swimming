## السباحة إلى اليسار واليمين

في السباحة المتزامنة ، يقوم فريق من السباحين بإجراء روتين منسَّق من الحركات للموسيقى.

لنبدأ بجلب قطة واحدة للسباحة.

--- task ---

افتح مشروع فارغ جديد في Scratch.

**Online**: open a [new online Scratch project](http://rpf.io/scratchnew){:target="_blank"}.

**Offline**: open a new project in the offline editor.

If you need to download and install the Scratch offline editor, you can find it at [rpf.io/scratchoff](http://rpf.io/scratchoff){:target="_blank"}.

--- /task ---

دعنا أولاً نحول المسرح إلى اللون الأزرق حتى يبدو وكأنه مسبح.

--- task ---

Click on the 'Stage' and then the 'Backdrops' Tab and 'Convert to Bitmap'.

![scratch screen with stage, backdrops and convert to bitmap highlighted](images/swim-select-backdrop.png)

--- /task ---

--- task ---

حدد اللون الأزرق وأداة "ملء بلون" ثم انقر على الخلفية.

![backdrops tab and fill tool selected](images/swim-fill.png)

--- /task ---

--- task ---

ستستخدم كائناً قطاً مختلفًا، لذا أنقر على علامة الخطأ الموجودة على القط الماشي لحذفه.

![delete menu selected](images/swim-delete.png)

--- /task ---

--- task ---

Choose the `Cat Flying` sprite from the library and add it to your project.

[[[generic-scratch3-sprite-from-library]]]

![Cat Flying sprite highlighted](images/swim-sprite.png)

تبدو القطة الطائرة وكأنها تسبح.

--- /task ---

--- task ---

الآن دعونا نجعل القط يسبح.

Select the 'Cat flying' sprite, click 'Code' and add the code to make the cat rotate left and right when you press the left and right arrow keys.

![الكائن السبّاح](images/swimmer-sprite.png)

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
