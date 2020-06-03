## Défi: coder ta propre chorégraphie

Peux-tu écrire ta propre chorégraphie de natation synchronisée à effectuer lorsque tu appuies sur la touche espace ou une autre touche?

Essaie d'abord de faire une chorégraphie en utilisant les touches fléchées.

Utilise les boucles `répéter`{:class="block3control"} pour effectuer les mêmes actions plusieurs fois.

Voici un exemple:

![sprite nageur](images/swimmer-sprite.png)

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

