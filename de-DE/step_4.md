## Erstelle das Team

Synchronschwimmen braucht mehr als eine Katze! Wir können `erzeuge Klon von`{:class="block3control"} verwenden, um Kopien zu erstellen, die sich auf die gleiche Weise verhalten.

--- task ---

Fügen wir zuerst Code hinzu, um sicherzustellen, dass die Katze immer an derselben Position startet, wenn du auf die grüne Flagge klickst.

![Schwimmer Figur](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

Teste deinen Code, indem du einige Pfeiltasten drückst und dann auf die grüne Flagge klickst, um zur Startposition zurückzukehren.

--- /task ---

--- task ---

Jetzt können wir eine `wiederhole`{:class="block3control"}-Schleife verwenden, um 6 Klone (Kopien) der Katze zu erstellen.

![Schwimmer Figur](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

Schleifen werden verwendet, um dasselbe mehrmals auszuführen.

--- /task ---

--- task ---

Du möchtest nicht, dass sich alle Katzen an derselben Position befinden!

Füge Code hinzu, um die Figur um 60 Grad zu drehen, bevor du den nächsten Klon erstellst.

![Schwimmer Figur](images/swimmer-sprite.png)

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

 Teste deinen Code mit den Pfeiltasten. Du solltest in der Lage sein, einige erstaunliche Synchronschwimmmuster zu erstellen!

![6 Katzen-Figuren in verschiedenen Positionen und Rotationen](images/swim-test-clones.png)

--- /task ---
