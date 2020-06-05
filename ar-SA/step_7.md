## تحدي: قم ببرمجة روتينك الخاص

هل يمكنك كتابة روتين السباحة المتزامن الخاص بك ليتم تنفيذه عندما تقوم بالضغط على مفتاح المسافة أو مفتاح آخر؟

جرب ممارسة روتين باستخدام مفاتيح الأسهم أولاً.

استخدم التعليمة`كرّر`{:class="block3control"} لتنفيذ نفس الإجراءات عدة مرات.

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

