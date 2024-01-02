## Pico riproduce un suono

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Un altro modo per comunicare è usare i suoni.
</div>
<div>

![Lo sprite Pico dice "Ciao!"](images/pico-step2.png){:width="300px"}

</div>
</div>

### Aggiungi un suono allo sprite Pico

--- task ---

Fai clic sulla scheda **Suoni** per lo sprite **Pico** e troverai un suono **pop**. Fai clic sull'icona **Play** per ascoltare il suono **pop**.

![Riproduzione del suono pop nella scheda Suoni.](images/pico-sound-play.png)

**Debug**: Se non riesci a sentire il suono controlla che l'audio sul tuo computer o sul tuo tablet funzioni.

--- /task ---

--- task ---

Per selezionare un nuovo suono, fai clic sull'icona **Scegli un Suono** e seleziona la categoria **Spazio** o scrivi `space` nella barra di ricerca.

![L'icona 'Scegli uno Suono'.](images/sound-button.png)

![L'editor Scratch con 'Scegli uno Suono' evidenziato.](images/pico-choose-sound.png)

![La categoria 'Spazio' nella libreria dei Suoni.](images/pico-space-category.png)

--- /task ---

--- task ---

Riproduci alcuni suoni diversi usando le icone **Play**. Quando hai trovato il suono che vuoi utilizzare, fai clic su di esso per aggiungerlo al progetto.

![Un suono di esempio (il suono Alien Creak1) mostrato sotto il suono pop nella scheda Suoni.](images/pico-inserted-sound.png)

--- /task ---

### Fai riprodurre il suono a Pico quando viene cliccato (o toccato)

--- task ---

Fai clic sulla scheda **Codice**. Nel menu dei blocchi `Suono`{:class="block3sound"}, cerca il blocco `avvia riproduzione suono`{:class="block3sound"}.

Trascina il blocco nell'area del Codice, tra il blocco `quando si clicca questo`{:class="block3events"} e il blocco `dire`{:class="block3looks"}. Si aprirà uno spazio vuoto e il blocco si incasterà nella posizione corretta.

![Il blocco 'avvia riproduzione suono' viene aggiunto tra i due blocchi.](images/pico-insert-block.gif)

Il tuo codice dovrebbe assomigliare a questo:

![Lo sprite Pico.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Ciao!] for [2] seconds // nascondi il fumetto dopo 2 secondi
```

--- /task ---

### Prova il tuo codice

--- task ---

Controlla che il blocco `avvia riproduzione suono`{:class="block3sound"} abbia il suono scelto da te. Se non lo ha, devi fare clic sul blocco `avvia riproduzione suono`{:class="block3sound"}, e poi seleziona il tuo suono nel menu a comparsa.

![Facendo clic sul suono Alien Creak1 nel menu a comparsa all'interno del blocco 'avvia riproduzione suono'.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Prova:** fai clic sullo sprite **Pico** e controlla che un fumetto appaia e che si senta un suono. Se non senti il suono, controlla di aver aggiunto il blocco `avvia riproduzione suono`{:class="block3sound"} sotto il blocco `quando si clicca questo sprite`{:class="block3events"}.

--- /task ---

