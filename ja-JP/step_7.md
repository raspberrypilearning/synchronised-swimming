## チャレンジ: 自分のルーティンをプログラムする

スペースキーまたは他のキーを押したときに実行される、自分だけのアーティスティック・スイミングのルーティンを書けますか？

まずは矢印キーを使ってルーティンを作ってみてください。

`ずっと`{:class="block3control"}ループを使うと、何回も同じ動作を実行します。

これは一例 (れい) です。

![泳ぐネコのスプライト](images/swimmer-sprite.png)

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

