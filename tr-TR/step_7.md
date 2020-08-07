## Meydan okuma: kendi rutininizi oluşturun

Boşluk tuşuna veya başka bir tuşa bastığınızda oluşacak bir senkronize yüzme rutinini kendiniz yazabilir misiniz?

Önce ok tuşlarını kullanarak rutin bir çalışma yapmayı deneyin.

Aynı işlemleri birden çok kez gerçekleştirmek için `tekrarla`{:class="block3control"} döngülerini kullanın.

İşte bir örnek:

![yüzücü kuklası](images/swimmer-sprite.png)

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

