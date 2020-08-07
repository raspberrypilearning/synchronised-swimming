## Kostüm değiştirme

Hmm, kedi kuklası sola döndüğünde yön değiştirirse daha iyi görünecek sanki.

--- task ---

'Kostümler'e tıklayın ve 'uçan kedi-a' kostümünü silin.

![kostümler sekmesi ve kostüm üzerinde vurgulanan sil simgesi](images/swim-delete-a.png)

--- /task ---

--- task ---

Kalan kostümün adı 'uçan kedi-b'yi 'sağ' olarak yeniden adlandırın.

![kostüm sekmesinde vurgulanan isim](images/swim-costume-right.png)

--- /task ---

--- task ---

Kostüm üzerinde sağ tıklayın ve kostümün bir kopyasını oluşturmak için çoğalt seçeneğini tıklayın.

![yinelemeleri vurgulanmış kostüm menüsü](images/swim-costume-duplicate.png)

--- /task ---

--- task ---

Kopyayı tersine çevirmek için 'Yatay Çevir'e tıklayın ve ardından ismini 'sol' olarak yapın.

Kostümünüz şöyle görünmeli:

![ismi vurgulanmış, döndür simgeli ve sola bakan yeni kostüm](images/swim-costume-left.png)

--- /task ---

--- task ---

Kodunuza dönmek için 'Kod'a tıklayın ve yön değiştiğinde kostümü değiştirmek için bloklar ekleyin.

![yüzücü kuklası](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
+switch costume to (left v)
turn ccw (15) degrees

when [right arrow v] key pressed
+switch costume to (right v)
turn cw (15) degrees
```

--- /task ---

--- task ---

Ok tuşlarını kullanıp sahne etrafında yüzerek kodunuzu test edin.

![sola bakan kukla](images/swim-test-left.png)

--- /task ---
