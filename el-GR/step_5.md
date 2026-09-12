## Ο Nano αλλάζει ενδυμασίες

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Θα κάνεις τον Nano να εκφράσει συναισθήματα αλλάζοντας **ενδυμασίες**.

Τα αντικείμενα έχουν **ενδυμασίες** για να αλλάζουν την εμφάνισή τους. Συνήθως είναι ελαφρώς διαφορετικές εικόνες του ίδιου αντικειμένου. Για να ζωντανέψεις ένα αντικείμενο, μπορείς να αλλάξεις την ενδυμασία του.

</div>
<div>

![Το αντικείμενο Nano που λέει, "Ευχαριστώ!"](images/nano-step-2.png){:width="300px"}

</div>
</div>

--- task ---

Πρόσθεσε το αντικείμενο **Nano** στο έργο σου από την κατηγορία **Φαντασία**.

![Το εικονίδιο «Επιλέξτε ένα Αντικείμενο».](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Βεβαιώσου ότι το αντικείμενο **Nano** είναι επιλεγμένο στη λίστα Αντικειμένων κάτω από την Σκηνή.

![Η λίστα Αντικειμένων, με ένα μπλε περίγραμμα γύρω από το αντικείμενο Nano για να δείξει ότι έχει επιλεγεί το Nano.](images/nano-selected.png)

Click on the **Code** tab and add a script to get the **Nano** sprite to change costume using `switch costume to`{:class="block3looks"} and `wait`{:class="block3control"}. Χρησιμοποίησε το αναπτυσσόμενο μενού για εναλλαγή μεταξύ του `nano-b`{:class="block3looks"} και του `nano-a`{:class="block3looks"}:

![Το αντικείμενο Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // όταν γίνει κλικ στον Nano
switch costume to [nano-b v] // ο Nano μιλάει
wait (0.5) seconds // δοκίμασε 0.25 αντί για 0.5
switch costume to [nano-a v] // ο Nano χαμογελάει
```
--- /task ---

**Συμβουλή:** Όλα τα μπλοκ είναι χρωματικά κωδικοποιημένα, επομένως θα βρεις το μπλοκ `άλλαξε ενδυμασία σε`{:class="block3looks"} στο μενού μπλοκ `Όψεις`{:class="block3looks"} και το μπλοκ `περίμενε`{:class="block3looks"} στο μενού μπλοκ `Έλεγχος`{:class="block3looks"}.

--- task ---

**Δοκιμή:** Κάνε κλικ στο αντικείμενο **Nano** στην Σκηνή και έλεγξε ότι εμφανίζεται το συννεφάκι ομιλίας και ότι αλλάζει το κοστούμι του Nano.

--- /task ---
