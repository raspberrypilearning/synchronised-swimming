## Herausforderung: Programmiere deine eigene Routine

Kannst du deine eigene Synchronschwimmroutine schreiben, die ausgeführt wird, wenn du die Leertaste oder eine andere Taste drückst?

Versuche zuerst, eine Routine mit den Pfeiltasten auszuarbeiten.

Verwende `wiederhole`{:class="block3control"}-Schleifen, um dieselben Aktionen mehrmals auszuführen.

Hier ist ein Beispiel:

![Schwimmer Figur](images/swimmer-sprite.png)

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

