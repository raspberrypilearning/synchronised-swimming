## Herausforderung: Programmiere deine eigene Routine

Kannst du deine eigene Synchronschwimmroutine schreiben, die ausgeführt wird, wenn du die Leertaste oder eine andere Taste drückst?

Versuche zuerst, eine Routine mit den Pfeiltasten auszuarbeiten.

Verwende `wiederhole`{:class="block3control"}-Schleifen, um dieselben Aktionen mehrmals auszuführen.

Hier ist ein Beispiel:

![Schwimmer Figur](images/swimmer-sprite.png)

```blocks3
wenn Taste [m V] gedrückt wird
wiederhole (8) mal
  drehe dich im Uhrzeigersinn um (45) Grad
  wiederhole (20) mal
    gehe (5) er Schritt
  Ende
  wiederhole (20) mal
    gehe (-5) er Schritt
  Ende
Ende
```

