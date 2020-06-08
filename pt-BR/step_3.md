## Trocando de fantasia

Hmm, isso ficaria melhor se o gato mudasse de direção quando virar à esquerda.

--- task ---

Clique em 'Fantasia' e exclua a fantasia 'gato voando'.

![Aba de "vestuário" e ícone de "deletar" estão destacados no traje](images/swim-delete-a.png)

--- /task ---

--- task ---

Renomeie o traje restante de 'gato voando' para 'direita'.

![nome à direita destacado na guia fantasia](images/swim-costume-right.png)

--- /task ---

--- task ---

Clique com o botão direito no vestuário e selecione duplicar para criar uma cópia

![menu de fantasia com duplicado destacado](images/swim-costume-duplicate.png)

--- /task ---

--- task ---

Clique em 'Giro Horizontal' para reverter a cópia e nomeie-a como 'esquerda'.

Suas fantasias devem ficar assim:

![nova fantasia está à esquerda com o ícone de giro e o nome destacado](images/swim-costume-left.png)

--- /task ---

--- task ---

Clique em 'Código' para retornar ao seu código e adicionar blocos para mudar a fantasia quando a direção for alterada.

![Gato nadador](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
+switch costume to (esquerda v)
turn ccw (15) degrees

when [right arrow v] key pressed
+switch costume to (direita v)
turn cw (15) degrees
```

--- /task ---

--- task ---

Teste seu código nadando pelo palco usando as teclas de seta do teclado

![Gato virando para a esquerda](images/swim-test-left.png)

--- /task ---
