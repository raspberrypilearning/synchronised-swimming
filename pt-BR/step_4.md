## Crie uma equipe

A natação sincronizada precisa de mais de um gato! Podemos usar `criar um clone`{:class="block3control"} para criar cópias que se comportam da mesma maneira.

--- task ---

Primeiro, vamos adicionar um código para garantir que o gato sempre comece na mesma posição quando você clicar na bandeira verde.

![Gato nadador](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

Teste seu código pressionando as teclas de seta e, em seguida, clicando na bandeira verde para retornar à posição inicial.

--- /task ---

--- task ---

Agora podemos usar a `repetição`{:class="block3control"} para criar 6 clones (cópias) do gato.

![Gato nadador](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

Laços de repetição são usados para fazer a mesma coisa várias vezes.

--- /task ---

--- task ---

Você não quer que todos os gatos estejam na mesma posição!

Adicione o código para girar 60 graus antes de criar cada cópia

![Gato nadador](images/swimmer-sprite.png)

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

 Teste seu código usando as teclas de seta do teclado Você deve conseguir criar incríveis padrões de natação sincronizada!

![6 gatos, todos em diferentes posições e rotações](images/swim-test-clones.png)

--- /task ---
