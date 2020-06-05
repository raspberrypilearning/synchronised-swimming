## أنشئ الفريق

السباحة المتزامنة تحتاج إلى أكثر من قطة واحدة! يمكننا استخدام `أنشئ نسخة من`{:class="block3control"} لإنشاء نسخ تتصرف بنفس الطريقة.

--- task ---

أولاً دعونا نضيف تعليمة برمجية للتأكد من أن القط يبدأ دائماً في نفس الموضع عند النقر على العلم الأخضر.

![الكائن السبّاح](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

اختبر التعليمات البرمجية الخاصة بك بالضغط على بعض مفاتيح الأسهم ثم انقر فوق العلم الأخضر للعودة إلى موضع البداية.

--- /task ---

--- task ---

الآن يمكننا استخدام التعليمة`كرّر`{:class="block3control"} لإنشاء 6 نسخ من القطة.

![الكائن السبّاح](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

تستخدم التعليمة (تكرار) للقيام بنفس الشيء عدة مرات.

--- /task ---

--- task ---

لا تريد أن تكون جميع القطط في نفس الوضع!

أضف تعليمة برمجية للتدوير 60 درجة قبل إنشاء كل نسخة.

![الكائن السبّاح](images/swimmer-sprite.png)

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

 اختبر التعليمات البرمجية الخاصة بك باستخدام مفاتيح الأسهم. يجب أن تكون قادراً على إنشاء بعض أنماط السباحة المتزامنة المذهلة!

![6 كائنات من القطط جميعها في مواقع ومواضع دوران مختلفة](images/swim-test-clones.png)

--- /task ---
