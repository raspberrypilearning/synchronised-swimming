## Δημιουργία ομάδας

Η συγχρονισμένη κολύμβηση χρειάζεται περισσότερες από μία γάτες! Μπορούμε να χρησιμοποιήσουμε το μπλοκ `δημιούργησε κλώνο του`{:class="block3control"} για τη δημιουργία αντιγράφων που συμπεριφέρονται με τον ίδιο τρόπο.

--- task ---

Αρχικά ας προσθέσουμε κώδικα για να βεβαιωθούμε ότι η γάτα ξεκινά πάντα στην ίδια θέση, όταν κάνεις κλικ στην πράσινη σημαία.

![αντικείμενο κολυμβητή](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

Δοκίμασε τον κώδικά σου πατώντας μερικές φορές τα βελάκια και στη συνέχεια κάνοντας κλικ στην πράσινη σημαία για να επιστρέψεις στην αρχική θέση.

--- /task ---

--- task ---

Τώρα μπορούμε να χρησιμοποιήσουμε ένα βρόχο `επανάλαβε`{:class="block3control"} για τη δημιουργία 6 κλώνων (αντιγράφων) της γάτας.

![αντικείμενο κολυμβητή](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

Οι βρόχοι χρησιμοποιούνται για να κάνουν το ίδιο πράγμα πολλές φορές.

--- /task ---

--- task ---

Δεν θέλεις όλες οι γάτες να βρίσκονται στην ίδια θέση!

Πρόσθεσε κώδικα για να περιστρέφεται κατά 60 μοίρες πριν δημιουργήσεις κάθε κλώνο.

![αντικείμενο κολυμβητή](images/swimmer-sprite.png)

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

 Δοκίμασε τον κωδικά σου χρησιμοποιώντας τα βελάκια. Θα πρέπει να μπορείς να δημιουργήσεις μερικά καταπληκτικά σχέδια συγχρονισμένης κολύμβησης!

![6 αντικείμενα γάτας σε διαφορετικές θέσεις και περιστροφές](images/swim-test-clones.png)

--- /task ---
