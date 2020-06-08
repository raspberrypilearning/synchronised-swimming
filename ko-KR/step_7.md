## 도전 과제: 나만의 안무 프로그래밍하기

스페이스 키나 다른 키를 누를 때 수행할 리듬 수영 안무를 작성해볼까요?

화살표 키를 사용한 동작을 먼저 시도해보세요.

동일한 작업을 여러 번 수행하기 위해 `반복하기`{:class="block3control"}를 사용할 수 있습니다.

아래 예제를 참고하세요:

![수영하는 고양이 스프라이트](images/swimmer-sprite.png)

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

