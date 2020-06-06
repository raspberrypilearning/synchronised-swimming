## Desafio: codifique sua própria rotina

Você pode escrever sua própria rotina de natação sincronizada a ser executada ao pressionar a tecla espaço ou outra tecla?

Primeiro, tente elaborar uma rotina usando as teclas de seta.

Use `repetir` {: class = "block3control"} e faça rotações para executar as mesmas ações várias vezes.

Aqui está um exemplo:

![Gato nadador](images/swimmer-sprite.png)

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

