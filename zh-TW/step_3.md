## 改變造型

Hmm, this would look better if the cat sprite changed direction when it turns left.

--- task ---

點擊“服裝”並刪除“超人貓-a”的服裝。

![costumes tab and delete icon highlighted on costume](images/swim-delete-a.png)

--- /task ---

--- task ---

Rename the remaining costume from 'cat flying-b' to 'right'.

![name right highlighted in costumes tab](images/swim-costume-right.png)

--- /task ---

--- task ---

Right-click on the costume and choose duplicate to create a copy.

![costume menu with duplicate highlighted](images/swim-costume-duplicate.png)

--- /task ---

--- task ---

單擊“水平翻轉”以反轉複製，然後取名為“左”。

你的服裝應該會像這樣：

![new costume facing left with flip icon and name highlighted](images/swim-costume-left.png)

--- /task ---

--- task ---

Click 'Code' to return to your code and add blocks to change the costume when the direction is changed.

![水上精靈貓](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
+switch costume to (left v)
turn ccw (15) degrees

when [right arrow v] key pressed
+switch costume to (right v)
turn cw (15) degrees
```

--- /task ---

--- task ---

用方向鍵來測試你的寫好的程式，看看你能不能讓精靈貓在舞台上游泳。

![精靈貓向左](images/swim-test-left.png)

--- /task ---
