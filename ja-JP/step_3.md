## コスチュームをかえる

うーん、ネコのスプライトが左に向いたときには、向きをかえた方が見た目が良いですね。

--- task ---

「コスチューム」をクリックして「cat flying-a」コスチュームを削除します。

![コスチュームタブと削除アイコンが強調されている](images/swim-delete-a.png)

--- /task ---

--- task ---

のこったコスチュームの名前を「cat flying-b」から「右」にかえます。

![コスチュームタブで強調された名前「右」](images/swim-costume-right.png)

--- /task ---

--- task ---

コスチュームを右クリックし、「複製」（ふくせい）をえらんでコピーを作ります。

![コスチュームのメニューで「複製」が強調されている](images/swim-costume-duplicate.png)

--- /task ---

--- task ---

「左右反転」のアイコンをクリックし、コピーしたものを反転して、名前を「左」にします。

コスチュームは次のようになります。

![反転アイコンと名前が強調された、左を向いた新しいコスチューム](images/swim-costume-left.png)

--- /task ---

--- task ---

「コード」をクリックしてコードにもどり、ブロックを追加して向きがかわったらコスチュームもかわるようにします。

![泳ぐネコのスプライト](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
+switch costume to (左 v)
turn ccw (15) degrees

when [right arrow v] key pressed
+switch costume to (右 v)
turn cw (15) degrees
```

--- /task ---

--- task ---

矢印キーを使い、ステージ中を泳いでコードをテストしましょう。

![左を向いたスプライト](images/swim-test-left.png)

--- /task ---
