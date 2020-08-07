## Crea una squadra

Il nuoto sincronizzato ha bisogno di più di un gatto! Possiamo usare `crea clone di`{:class="block3control"} per creare copie che si comportano allo stesso modo.

--- task ---

Prima aggiungiamo il codice per assicurarci che il gatto inizi sempre nella stessa posizione quando fai clic sulla bandierina verde.

![nuotatore sprite](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

Prova il tuo codice premendo alcuni tasti freccia e poi fai clic sulla bandierina verde per tornare alla posizione iniziale.

--- /task ---

--- task ---

Adesso possiamo usare un ciclo `ripeti`{:class="block3control"} per creare 6 cloni (copie) del gatto.

![nuotatore sprite](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

I cicli vengono utilizzati per fare la stessa cosa più volte.

--- /task ---

--- task ---

Non vuoi che tutti i gatti si trovino nella stessa posizione!

Aggiungi il codice per ruotare di 60 gradi prima di creare ogni clone.

![nuotatore sprite](images/swimmer-sprite.png)

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

 Verifica il tuo codice utilizzando i tasti freccia. Dovresti essere in grado di creare alcuni fantastici schemi di nuoto sincronizzato!

![6 gatti sprite tutti in diverse posizioni e rotazioni](images/swim-test-clones.png)

--- /task ---
