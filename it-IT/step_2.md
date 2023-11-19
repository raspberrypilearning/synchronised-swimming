## Nuotare a sinistra e a destra

Nel nuoto sincronizzato una squadra di nuotatori esegue una routine coordinata di mosse seguendo la musica.

Cominciamo a fare nuotare un singolo gatto.

--- task ---

Inizia un nuovo progetto Scratch.

**Online**: open a [new online Scratch project](https://rpf.io/scratchnew){:target="_blank"}.

**Offline**: apri un nuovo progetto nell'editor offline.

If you need to download and install the Scratch offline editor, you can find it at [rpf.io/scratchoff](https://rpf.io/scratchoff){:target="_blank"}.

--- /task ---

Prima coloriamo lo Stage di blu in modo che sembri una piscina.

--- task ---

Clicca su 'Stage', poi sulla scheda 'Sfondi' e infine 'Converti in Bitmap'.

![schermo scratch con stage, sfondi e converti in bitmap evidenziati](images/swim-select-backdrop.png)

--- /task ---

--- task ---

Seleziona un colore blu e lo strumento "Riempimento con colore" e poi fai clic sullo sfondo.

![scheda sfondi e strumento di riempimento selezionato](images/swim-fill.png)

--- /task ---

--- task ---

Utilizzerai uno sprite di gatto diverso, quindi fai clic sulla x per cancellare il gatto che cammina.

![menu elimina selezionato](images/swim-delete.png)

--- /task ---

--- task ---

Scegli lo sprite `Cat Flying` dalla libreria e aggiungilo al tuo progetto.

[[[generic-scratch3-sprite-from-library]]]

![Cat Flying sprite evidenziato](images/swim-sprite.png)

Il gatto volante sembra che stia nuotando.

--- /task ---

--- task ---

Adesso facciamo nuotare il gatto.

Seleziona lo sprite 'Cat flying', fai clic su "Codice" e aggiungi il codice per far ruotare il gatto a destra e sinistra quando premi i tasti freccia sinistra e destra.

![sprite nuotatore](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
turn ccw (15) degrees

when [right arrow v] key pressed
turn cw (15) degrees
```

--- /task ---

--- task ---

Testa il tuo codice premendo i tasti freccia sinistra e destra sulla tastiera.

![gatto sprite ruotato a destra](images/swim-right.png)

--- /task ---

--- task ---

E aggiungi il codice per il movimento avanti e indietro.

![sprite nuotatore](images/swimmer-sprite.png)

```blocks3
when [up arrow v] key pressed
move (10) steps

when [down arrow v] key pressed
move (-10) steps 
```

--- /task ---

--- task ---

Prova il tuo codice nuotando intorno al palcoscenico utilizzando i tasti freccia.

--- /task ---
