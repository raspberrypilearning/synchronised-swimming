## Πρόκληση: δημιούργησε τη δική σου ρουτίνα

Μπορείς να γράψεις τη δική σου ρουτίνα συγχρονισμένης κολύμβησης που θα εκτελείται όταν πατάς το πλήκτρο διαστήματος ή κάποιο άλλο πλήκτρο;

Δοκίμασε πρώτα να κάνεις μια ρουτίνα χρησιμοποιώντας τα βελάκια.

Χρησιμοποίησε βρόχους `επανάλαβε`{:class="block3control"} για την εκτέλεση των ίδιων ενεργειών πολλές φορές.

Ακολουθεί ένα παράδειγμα:

![αντικείμενο κολυμβητή](images/swimmer-sprite.png)

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

