## Changement de costume

Hmm, cela aurait l'air mieux si le sprite de chat changeait de direction quand il tourne à gauche.

--- task ---

Clique sur «Costumes» et supprime le costume «chat volant-a».

![onglet costumes et supprimer l'icône en surbrillance sur le costume](images/swim-delete-a.png)

--- /task ---

--- task ---

Renomme le costume restant, de «chat volant-b» en «droite».

![nom à droite mis en surbrillance dans l'onglet costumes](images/swim-costume-right.png)

--- /task ---

--- task ---

Fais un clic droit sur le costume et choisis dupliquer pour créer une copie.

![menu costume avec doublon mis en surbrillance](images/swim-costume-duplicate.png)

--- /task ---

--- task ---

Clique sur «Retourner horizontalement» pour inverser la copie, puis nomme-la «gauche».

Tes costumes devraient ressembler à ceci:

![nouveau costume orienté vers la gauche avec icône retourner et nom en surbrillance](images/swim-costume-left.png)

--- /task ---

--- task ---

Clique sur «Code» pour retourner à ton code et ajoute des blocs pour changer le costume lorsque la direction est changée.

![sprite nageur](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
+switch costume to (gauche v)
turn ccw (15) degrees

when [right arrow v] key pressed
+switch costume to (droite v)
turn cw (15) degrees
```

--- /task ---

--- task ---

Teste ton code en nageant sur la scène en utilisant les touches fléchées.

![sprite orienté vers la gauche](images/swim-test-left.png)

--- /task ---
