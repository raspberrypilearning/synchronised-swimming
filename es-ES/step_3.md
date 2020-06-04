## Cambiando el disfraz

Hmm, esto se vería mejor si el objeto gato cambiara de dirección cuando gire a la izquierda.

--- task ---

Haga clic en 'Disfraces' y elimina el disfraz 'gato volador-a'.

![pestañas de disfraces y borrar icono resaltado en el disfraz](images/swim-delete-a.png)

--- /task ---

--- task ---

Cambia el nombre del disfraz que queda de 'gato volador-b' a 'derecha'.

![nombre destacado en la pestaña de disfraces](images/swim-costume-right.png)

--- /task ---

--- task ---

Haz clic en el botón derecho sobre el disfraz y luego haz clic en Duplicar para crear una copia.

![menú de disfraz con doble resaltado](images/swim-costume-duplicate.png)

--- /task ---

--- task ---

Haga clic en 'Voltear horizontalmente' para invertir la copia y luego asígnala el nombre 'izquierda'.

Tus disfraces deberían verse así:

![nuevo disfraz que mira a la izquierda con icono y nombre resaltados](images/swim-costume-left.png)

--- /task ---

--- task ---

Haga clic en 'Código' para volver al código y agrega estos bloques para cambiar el disfraz cuando se cambia la dirección.

![objeto nadador](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
+switch costume to (left v)
turn ccw (15) degrees

when [right arrow v] key pressed
+switch costume to (right v)
turn cw (15) degrees
```

--- /task ---

--- task ---

Prueba el código nadando alrededor del escenario usando las flechas del teclado.

![objeto mirando a la izquierda](images/swim-test-left.png)

--- /task ---
