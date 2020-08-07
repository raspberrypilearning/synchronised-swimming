## Sfida: crea la tua routine personale

Puoi scrivere la tua routine di nuoto sincronizzato da eseguire quando viene premuto il tasto spazio o un altro tasto?

Prova a inventare una routine utilizzando prima i tasti freccia.

Usa il ciclo `ripeti`{:class="block3control"} per eseguire le stesse azioni più volte.

Ecco un esempio:

![nuotatore sprite](images/swimmer-sprite.png)

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

