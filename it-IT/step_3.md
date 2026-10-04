## Pico dice Ciao

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Uno sprite può avere del codice, dei costumi e dei suoni per cambiare il suo aspetto e quello che fa. 
  
Aggiungi blocchi di codice per far parlare Pico o per fargli emettere suoni quando lo si clicca.
</div>
<div>

![Lo sprite Pico dice "Ciao!"](images/pico-step2.png){:width="300px"}

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Le <span style="color: #0faeb0">**Emoticon**</span> servono a dare una personalità al personaggio nel gioco. Possono usare parole, suoni, movimenti, o effetti grafici, proprio come in Scratch. Hai mai giocato a un gioco che utilizza le emoticon?
</p>

### Usa il blocco dire

--- task ---

Apri il menu dei blocchi `Aspetto`{:class="block3looks"}.

Fai clic sul blocco `dire`{:class="block3looks"} `Ciao!``per`{:class="block3looks"} `2` `secondi`{:class="block3looks"}.

![Il blocco 'dire Ciao! per 2 secondi' si illumina con un contorno giallo.](images/pico-say-hello-blocks-menu.png)

Lo sprite **Pico** mostrerà un fumetto per due secondi.

![Lo sprite Pico con "Ciao!" in un fumetto.](images/pico-say-hello-stage.png)

**Suggerimento:** I blocchi di codice in Scratch si illuminano con un contorno giallo quando sono in esecuzione.

--- /task ---

--- task ---

Trascina il blocco `dire`{:class="block3looks"} `Ciao!``per`{:class="block3looks"} `2` `secondi`{:class="block3looks"} nell'area del Codice. Clicca sul blocco di nuovo.

![Trascinando il blocco 'dire' nell'area del Codice e facendo clic su di esso per eseguirlo.](images/pico-drag-say.gif)

![Il blocco 'dire' è stato trascinato nell'area del Codice. Il blocco di codice si illumina con un contorno giallo.](images/pico-drag-say.png)

--- /task ---

### Fai parlare Pico quando viene cliccato (o toccato)

--- task ---

Trascina un blocco `quando si clicca su questo sprite`{:class="block3events"} dal menu dei blocchi `Situazioni`{:class="block3events"} e connettilo alla parte superiore del blocco `dire`{:class="block3looks"} nell'area del Codice. I blocchi si incastreranno insieme.

![Un'animazione dei blocchi che si agganciano insieme. Quando si fa clic su Pico, dice "Ciao!" per due secondi.](images/pico-snap-together.gif)

![Lo sprite Pico.](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Commenti al Codice

--- task ---

```blocks3
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
Vedrai i commenti negli esempi di codice. Non serve che aggiungi i commenti quanto aggiungi codice al tuo progetto.

Se hai tempo quando hai finito il progetto, è una buona idea aggiungere commenti al codice così sarà più facile da capire. Try adding a comment now. Per aggiungere un commento, fai clic con il pulsante destro (o su un tablet, tocca e tieni premuto) su un blocco nell'area del Codice e seleziona **Aggiungi commento**.

![Il menu a comparsa che appare quando fai clic con il pulsante destro del mouse su un blocco. È selezionato "Aggiungi commento".](images/add-comment.png)

--- /task ---

### Prova

--- task ---

**Prova:** fai clic sullo sprite **Pico** sullo Stage e controlla che un fumetto appaia per due secondi. È importante provare il tuo codice per verificare che faccia ciò che ti aspetti.

--- /task ---

--- task ---

Hai già salvato il tuo progetto e gli hai dato un nome. Scratch ora lo salverà **automaticamente** per te.

Puoi comunque fare click su salva se ti va, per essere sicuro.

--- /task ---
