## 向左游、向右游

In synchronised swimming a team of swimmers perform a coordinated routine of moves to music.

Let's start by getting one cat swimming.

--- task ---

建立一個新的 Scratch 專案。

**線上版**: 開啟一個[新的線上Scratch專案](http://rpf.io/scratchnew){:target="_blank"}.

**離線版**: 在離線編輯器開啟新專案。

如果你需要下載 Scratch 離線版編輯器，可以連結到 [rpf.io/scratchoff](http://rpf.io/scratchoff){:target="_blank"}。

--- /task ---

首先，讓我們將舞台顏色換成藍色，這樣看起來會像是個游泳池。

--- task ---

點擊“舞台”、點擊“背景”標籤和“轉換成點陣圖”。

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

超人貓的姿勢看起來像在游泳。

--- /task ---

--- task ---

現在讓我們開始教貓游泳。

Select the 'Cat flying' sprite, click 'Code' and add the code to make the cat rotate left and right when you press the left and right arrow keys.

![水上精靈貓](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
turn ccw (15) degrees

when [right arrow v] key pressed
turn cw (15) degrees
```

--- /task ---

--- task ---

在鍵盤上按左/右箭頭鍵來測試你寫的程式。

![向右旋轉的精靈貓](images/swim-right.png)

--- /task ---

--- task ---

撰寫程式碼來控制精靈貓的前後移動。

![水上精靈貓](images/swimmer-sprite.png)

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
