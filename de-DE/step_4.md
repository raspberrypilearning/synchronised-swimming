## Erstelle das Team

Synchronschwimmen braucht mehr als eine Katze! Wir können `erzeuge Klon von`{:class="block3control"} verwenden, um Kopien zu erstellen, die sich auf die gleiche Weise verhalten.

--- task ---

Fügen wir zuerst Code hinzu, um sicherzustellen, dass die Katze immer an derselben Position startet, wenn du auf die grüne Flagge klickst.

![Schwimmer Figur](images/swimmer-sprite.png)

```blocks3
Wenn die grüne Flagge angeklickt wird
gehe zu x: (0) y: (0)
setze Richtung auf (90 v) Grad
```

--- /task ---

--- task ---

Teste deinen Code, indem du einige Pfeiltasten drückst und dann auf die grüne Flagge klickst, um zur Startposition zurückzukehren.

--- /task ---

--- task ---

Jetzt können wir eine `wiederhole`{:class="block3control"}-Schleife verwenden, um 6 Klone (Kopien) der Katze zu erstellen.

![Schwimmer Figur](images/swimmer-sprite.png)

```blocks3
Wenn die grüne Flagge angeklickt wird
gehe zu x: (0) y: (0)
setze Richtung auf (90 v) Grad
+wiederhole (6) mal
erzeuge Klon von (mir selbst v)
Ende
```

Schleifen werden verwendet, um dasselbe mehrmals auszuführen.

--- /task ---

--- task ---

Du möchtest nicht, dass sich alle Katzen an derselben Position befinden!

Füge Code hinzu, um die Figur um 60 Grad zu drehen, bevor du den nächsten Klon erstellst.

![Schwimmer Figur](images/swimmer-sprite.png)

```blocks3
Wenn die grüne Flagge angeklickt wird
gehe zu x: (0) y: (0)
setze Richtung auf (90 v) Grad
wiederhole (6) mal
+ drehe dich im Uhrzeigersinn um (60) Grad
erstelle einen Klon von (mir selbst v)
Ende
```

--- /task ---

--- task ---

 Teste deinen Code mit den Pfeiltasten. Du solltest in der Lage sein, einige erstaunliche Synchronschwimmmuster zu erstellen!

![6 Katzen-Figuren in verschiedenen Positionen und Rotationen](images/swim-test-clones.png)

--- /task ---
