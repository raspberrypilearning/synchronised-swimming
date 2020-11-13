## Maak het team

Om synchroon te zwemmen heb je meer dan één kat nodig! We kunnen `kloon`{:class="block3control"} gebruiken om kopieën te maken die zich op dezelfde manier gedragen.

--- task ---

Laten we eerst code toevoegen om ervoor te zorgen dat de kat altijd op dezelfde positie begint wanneer je op de groene vlag klikt.

![zwemmer sprite](images/swimmer-sprite.png)

```blocks3
wanneer op de groene vlag wordt geklikt
ga naar x: (0) y: (0)
richt naar (90 v) graden
```

--- /task ---

--- task ---

Test de code door op enkele pijltoetsen te drukken en vervolgens op de groene vlag te klikken om terug te keren naar de startpositie.

--- /task ---

--- task ---

Nu kunnen we een lus `herhaal`{:class="block3control"} gebruiken om 6 klonen (kopieën) van de kat te maken.

![zwemmer sprite](images/swimmer-sprite.png)

```blocks3
wanneer op de groene vlag wordt geklikt
ga naar x: (0) y: (0)
richt naar (90 v) graden
+ herhaal (6)
maak een kloon van (mijzelf v)
einde
```

Lussen worden gebruikt om hetzelfde ding meerdere keren te doen.

--- /task ---

--- task ---

Je wilt niet dat alle katten op dezelfde plek zitten!

Voeg code toe om 60 graden te draaien voordat je een kloon maakt.

![zwemmer sprite](images/swimmer-sprite.png)

```blocks3
wanneer op de groene vlag wordt geklikt
ga naar x: (0) y: (0)
richt naar (90 v) graden
herhaal (6)
+ draai (60) graden naar rechts
maak een kloon van (mijzelf v)
einde
```

--- /task ---

--- task ---

 Test je code met behulp van de pijltjestoetsen. Je zou een aantal geweldige gesynchroniseerde zwempatronen moeten kunnen maken!

![6 katten sprites allemaal in verschillende posities en rotaties](images/swim-test-clones.png)

--- /task ---
