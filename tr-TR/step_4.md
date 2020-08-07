## Takım oluştur

Senkronize yüzme için birden fazla kedi gerekir! Aynı şekilde davranan kopyalar oluşturmak için `...'in ikizini yarat`{:class="block3control"} bloğunu kullanabiliriz.

--- task ---

Önce yeşil bayrağa tıkladığınızda kedinin her zaman aynı pozisyonda başladığından emin olmak için kod ekleyelim.

![yüzücü kuklası](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

Bazı ok tuşlarına basıp kodunuzu test edin ve daha sonra yeşil bayrağı tıklayarak başlangıç konumuna geri dönün.

--- /task ---

--- task ---

Kedinin 6 klonunu (kopyasını) oluşturmak için `tekrarla`{: class = "block3control"} döngüsünü şimdi kullanabiliriz.

![yüzücü kuklası](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

Döngüler aynı şeyi birden çok kez yapmak için kullanılır.

--- /task ---

--- task ---

Tüm kedilerin aynı pozisyonda olmasını istemiyorsunuz!

Her bir klonu oluşturmadan önce 60 derece dönmesi için kod ekleyin.

![yüzücü kuklası](images/swimmer-sprite.png)

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

 Ok tuşlarını kullanarak kodunuzu test edin. Artık bir takım etkileyici senkronize yüzme desenleri oluşturabileceksiniz!

![farklı pozisyon ve rotasyonlarda 6 kedi kuklası](images/swim-test-clones.png)

--- /task ---
