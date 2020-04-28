## Uitdaging: maak je eigen routine

Kun je jouw eigen gesynchroniseerde zwemroutine schrijven die moet worden uitgevoerd wanneer je op de spatiebalk of een andere toets drukt?

Probeer eerst een routine uit te werken met behulp van de pijltjestoetsen.

Gebruik `herhaal`{:class="block3control"} lussen om dezelfde acties meerdere keren uit te voeren.

Hier is een voorbeeld:

![zwemmer sprite](images/swimmer-sprite.png)

```blocks3
wanneer [m v] is ingedrukt
herhaal (8)
    draai (45) graden naar rechts
    herhaal (20)
        neem (5) stappen
    einde
    herhaal (20)
        neem (-5) stappen
    einde
einde
```

