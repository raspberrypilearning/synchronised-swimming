## プログラムによるルーティン

ルーティンを完成 (かんせい) させて、かんたんに繰り返せるようにしたいと思いませんか？

--- task ---

スペースキーが押されたときの演技 (えんぎ) を追加してみましょう。

![泳ぐネコのスプライト](images/swimmer-sprite.png)

```blocks3
when [space v] key pressed
switch costume to (右 v)
repeat (36)
turn cw (10) degrees
move (10) steps
end
```

--- /task ---

--- task ---

プロジェクトを実行し、スペースキーを押して新しいルーティンをテストしましょう。

![泳ぎまわるスプライト](images/swim-routine.png)

スペースキーを押す前に矢印キーを使ってべつの位置に移動してみましょう。

--- /task ---




