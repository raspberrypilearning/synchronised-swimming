## Desafío: programa tu propia rutina

¿Puedes escribir tu propia rutina de natación sincronizada para que se ejecute cuando presiones la barra espaciadora u otra tecla?

Intenta elaborar una rutina usando las flechas del teclado primero.

Usa blucles `repetir`{:class="block3control"} para realizar las mismas acciones varias veces.

Aquí tienes un ejemplo:

![objeto nadador](images/swimmer-sprite.png)

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

