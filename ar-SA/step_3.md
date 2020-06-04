## تغيير المظهر

ممم، سيكون هذا أفضل إذا تغير إتجاه الكائن القط عندما يستدير إلى اليسار.

--- task ---

انقر على "المظاهر" واحذف مظهر"القط الطائر-أ".

![تم تمييز تبويب المظاهر وحذف أيقونة على المظهر](images/swim-delete-a.png)

--- /task ---

--- task ---

إعادة تسمية المظهر المتبقي من "القط الطائر-ب" إلى "يمين".

![تم تمييز اسم اليمين في تبويب المظاهر](images/swim-costume-right.png)

--- /task ---

--- task ---

انقر بزر الماوس الأيمن على المظهر ثم انقر فوق مضاعفة لإنشاء نسخة من المظهر.

![costume menu with duplicate highlighted](images/swim-costume-duplicate.png)

--- /task ---

--- task ---

أنقر فوق "إعكس أفقياً" لعكس النسخة ثم قم بتسميتها "يسار".

المظاهر الخاصة بك يجب أن تبدو هكذا:

![new costume facing left with flip icon and name highlighted](images/swim-costume-left.png)

--- /task ---

--- task ---

Click 'Code' to return to your code and add blocks to change the costume when the direction is changed.

![الكائن السبّاح](images/swimmer-sprite.png)

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

Test your code by swimming around the stage using the arrow keys.

![sprite facing left](images/swim-test-left.png)

--- /task ---
