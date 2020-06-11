## 挑戰：編排專屬的水上舞蹈

你可以寫出當按下空白鍵或其他按鍵後執行你所編排的水上芭蕾嗎？

試試看，能不能用方向鍵來執行舞蹈動作。

使用 `循環`{:class="block3control"}迴圈來執行多次同樣的動作。

這裡有個例子：

![水上精靈貓](images/swimmer-sprite.png)

```blocks3
when [m v] key pressed
repeat (8)
    turn cw (45) degrees
    repeat (20)
        move (5) steps
    end
    repeat (20)
        move (-5) steps
    end
end
```

