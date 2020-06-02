## تحدي: قم ببرمجة روتينك الخاص

هل يمكنك كتابة روتين السباحة المتزامن الخاص بك ليتم تنفيذه عندما تقوم بالضغط على مفتاح المسافة أو مفتاح آخر؟

Try working out a routine using the arrow keys first.

Use `repeat`{:class="block3control"} loops to perform the same actions multiple times.

إليك مثالاً:

![الكائن السباح](images/swimmer-sprite.png)

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

