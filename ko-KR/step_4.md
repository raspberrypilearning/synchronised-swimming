## 팀 만들기

리듬 수영에는 하나 이상의 고양이가 필요하죠! 우리는 `복제하기`{:class="block3control"}을 사용하여 같은 방식으로 행동하는 복제본을 만들 수 있습니다.

--- task ---

먼저 녹색 깃발을 클릭할 때 고양이가 항상 같은 위치에서 시작하도록 코드를 추가하겠습니다.

![수영하는 고양이 스프라이트](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

화살표 키를 몇 번 눌러 움직여 준 다음 녹색 깃발을 클릭하여 시작 위치로 돌아가는지 확인하세요.

--- /task ---

--- task ---

이제 `반복하기`{:class="block3control"} 블록을 사용하여 6개의 복제본(복사본)을 만들 것입니다.

![수영하는 고양이 스프라이트](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

반복하기는 같은 일을 여러 번 처리하는 데에 사용합니다.

--- /task ---

--- task ---

물론 모든 고양이가 같은 위치에 있는 것을 원하는 것은 아니겠죠!

각 클론을 만들기 전에 60도씩 회전하는 코드를 추가하세요.

![수영하는 고양이 스프라이트](images/swimmer-sprite.png)

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

 화살표 키를 사용하여 코드의 동작을 확인하세요. 재미있는 리듬 수영 패턴을 만들 수 있을 것입니다!

![서로 다른 위치와 방향을 가진 6개의 고양이 스프라이트](images/swim-test-clones.png)

--- /task ---
