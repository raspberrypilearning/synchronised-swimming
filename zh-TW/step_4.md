## 建立隊伍

水上芭蕾需要更多舞者！ 我們可以使用`建立分身`{:class="block3control"}來建立一模一樣動作的分身。

--- task ---

首先讓我們來寫一段程式，來確保當你點擊綠旗的時候，貓都是從同一個位置開始的。

![水上精靈貓](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

測試你寫的的程式：透過按上下左右方向鍵和點擊綠旗，會不會回到原始位置來。

--- /task ---

--- task ---

現在我們可以使用`repeat`{:class="block3control"}迴圈來創建6隻貓的分身（副本）。

![水上精靈貓](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

迴圈是用於執行多次一樣的動作。

--- /task ---

--- task ---

你不會想所有的舞者（貓）都在同個位置上！

創建每個分身之前，增加一段旋轉60度的程式。

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

![6隻精靈貓都在不同的角度和位置](images/swim-test-clones.png)

--- /task ---
