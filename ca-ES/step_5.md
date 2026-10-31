## En Nano canvia de vestit

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Fes que Nano cobri vida i és canvi els vestits.

Els personatges tenen vestits per canviar la seva aparença. Normalment són imatges lleugerament diferents del mateix personatge. Per animar personatges, tu pots canviar els seus vestits.

</div>
<div>

![The Nano sprite with arms out](images/nano-b-demo.png){:width="300px"}

</div>
</div>

--- task ---

Afegeix el personatge d'en  **Nano**  al teu projecte des de la categoria  **Fantasia**.

![La icona "Tria un Personatge".](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Assegureu-vos que el personatge d'en **Nano** estigui seleccionat a la llista de Personatges a sota de l'escenari.

![La llista de personatges, amb una vora blava al voltant del personatge d'en Nano per mostrar que Nano està seleccionat.](images/nano-selected.png)

Click on the **Code** tab and add a script to get the **Nano** sprite to change costume using `switch costume to`{:class="block3looks"} and `wait`{:class="block3control"}. Utilitzeu el menú desplegable per canviar entre `nano-b`{:class="block3looks"} i `nano-a`{:class="block3looks" }:

![El personatge d'en Pico.](images/nano-sprite.png)

```blocks3
when this sprite clicked // quan facis clic a Nano
switch costume to [nano-b v] // El Nano parlant
wait (0.5) seconds // prova 0,25 en lloc de 0,5
switch costume to [nano-a v] // Nano somrient
```
--- /task ---

**Consell:** Tots els blocs estan codificats per colors, així podras trobar el bloc `canvi de vestit`{:class="block3looks"} en  el bloc de menú `Aspecte`{:class="block3looks"} i el bloc d'`espera`{:class="block3control"} en el bloc de menu de `Control`{:class="block3control"}.

--- task ---

**Prova:** Feu clic al personatge d'en **Nano**  a l'escenari i comproveu que el vestit d'en Nano canvia.

--- /task ---
