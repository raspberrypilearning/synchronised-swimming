## チャレンジ: 自分のルーティンをプログラムする

Can you write your own synchronised swimming routine to be performed when you press the space key or another key?

まずは矢印キーを使ってルーティンを作ってみてください。

Use `repeat`{:class="block3control"} loops to perform the same actions multiple times.

Here's an example:

![swimmer sprite](images/swimmer-sprite.png)

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

