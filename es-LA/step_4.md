## Crear el equipo

¡La natación sincronizada necesita más de un gato! Podemos usar `crear clon de`{:class="block3control"} para crear copias que se comporten de la misma manera.

--- task ---

Primero vamos a añadir código para asegurarnos de que el gato siempre comienza en la misma posición cuando hagas clic en la bandera verde.

![objeto nadador](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

Prueba el código presionando algunas flechas del teclado y luego haz clic en la bandera verde para volver a la posición de inicio.

--- /task ---

--- task ---

Ahora podemos usar un bucle `repetir`{:class="block3control"} para crear 6 clones (copias) del gato.

![objeto nadador](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

Los bucles se usan para hacer lo mismo varias veces.

--- /task ---

--- task ---

¡Tú no quieres que todos los gatos estén en la misma posición!

Agrega código para girar 60 grados antes de crear cada clon.

![objeto nadador](images/swimmer-sprite.png)

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

 Prueba el programa utilizando las flechas del teclado. ¡Deberías poder crear algunos patrones de nado sincronizado increíbles!

![6 objetos de gato en diferentes posiciones y rotaciones](images/swim-test-clones.png)

--- /task ---
