## Créer l'équipe

La natation synchronisée a besoin de plus d'un chat ! Nous pouvons utiliser `créer un clone de`{:class="block3control"} pour créer des copies qui se comportent de la même manière.

--- task ---

Commençons par ajouter du code pour s'assurer que le chat commence toujours dans la même position lorsque tu cliques sur le drapeau vert.

![sprite nageur](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

Teste ton code en appuyant sur quelques touches fléchées, puis clique sur le drapeau vert pour retourner à la position de départ.

--- /task ---

--- task ---

Maintenant nous pouvons utiliser une boucle `répéter`{:class="block3control"} pour créer 6 clones (copies) du chat.

![sprite nageur](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

Les boucles sont utilisées pour faire la même chose plusieurs fois.

--- /task ---

--- task ---

Tu ne veux pas que tous les chats soient dans la même position !

Ajoute du code pour faire pivoter de 60 degrés avant de créer chaque clone.

![sprite nageur](images/swimmer-sprite.png)

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

 Teste ton code en utilisant les touches fléchées. Tu devrais être en mesure de créer des modèles de natation synchronisés incroyables !

![6 sprites chat tous en différentes positions et rotations](images/swim-test-clones.png)

--- /task ---
