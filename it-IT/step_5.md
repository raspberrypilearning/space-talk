## Nano cambia il costume

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Fai in modo che Nano si esprima cambiano **costumi**.

Gli Sprite hanno **costumi** per cambiare il loro aspetto. They are usually slightly different images of the same sprite. Per animare uno sprite, puoi cambiargli il costume.

</div>
<div>

![lo Sprite nano dice, "Grazie!"](images/nano-step-2.png){:width="300px"}

</div>
</div>

--- task ---

Aggiungi lo sprite **Nano** al tuo progetto dalla categoria **Fantasia**.

![L'icona 'Scegli uno Sprite'.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Assicurati che lo sprite **Nano** sia selezionato nella lista degli Sprite sotto lo Stage.

![L'elenco degli Sprite, con un bordo blu attorno allo sprite Nano per mostrare che Nano è selezionato.](images/nano-selected.png)

Fai clic sulla scheda **Codice** e aggiungi uno script per fare in modo che lo sprite **Nano** ringrazi utilizzando `passa al costume`{:class="block3looks"} e `attendi`{:class="block3control"}: Use the drop down menu to switch between `nano-b`{:class="block3looks"} and `nano-a`{:class="block3looks"}:

![Lo sprite Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // quando si clicca su Nano
switch costume to [nano-b v] // Nano sta parlando
wait (0.5) seconds // prova 0.25 invece di 0.5
switch costume to [nano-a v] // Nano sorridente
```
--- /task ---

**Suggerimento:** Tutti i blocchi hanno un colore specifico, quindi troverai il blocco `passa al costume`{:class="block3looks"} nel menu dei blocchi `Aspetto`{:class="block3looks"} e il blocco `attendi`{:class="block3control"} nel menu dei blocchi `Controllo`{:class="block3control"}.

--- task ---

**Prova:** Fai clic sullo sprite **Nano** sullo Stage e controlla che Nano cambi il suo costume.

--- /task ---
