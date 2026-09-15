## Nano yn newid gwisgoedd

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Get Nano to emote by switching **costumes**.

Mae gan gorluniau **wisgoedd** sy'n newid y ffordd maen nhw'n edrych. They are usually slightly different images of the same sprite. To animate a sprite, you can change its costume.

</div>
<div>

![Corlun Nano yn dweud, "Diolch!"](images/nano-step-2.png){:width="300px"}

</div>
</div>

--- task ---

Ychwanega gorlun **Nano** at dy brosiect o'r categori **Ffantasi**.

![Yr eicon 'Dewiswch Gorlun'.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Gwna'n siŵr dy fod wedi dewis corlun **Nano** yn rhestr y Corluniau o dan y Llwyfan.

![Y rhestr Corluniau, gydag amlinell las o gwmpas corlun Nano i ddangos mai Nano sydd wedi'i ddewis.](images/nano-selected.png)

Click on the **Code** tab and add a script to get the **Nano** sprite to change costume using `switch costume to`{:class="block3looks"} and `wait`{:class="block3control"}. Use the drop down menu to switch between `nano-b`{:class="block3looks"} and `nano-a`{:class="block3looks"}:

![Corlun Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // pan fydd Nano yn cael ei glicio
switch costume to [nano-b v] // Nano yn siarad
say [Diolch!] for [2] seconds // rho gynnig ar 1 yn lle 2
switch costume to [nano-a v] // Nano yn gwenu
```
--- /task ---

**Awgrym:** Mae'r holl flociau wedi'u trefnu yn ôl eu lliw, felly bydd y bloc `newid gwisg i`{:class="block3looks"} yn y ddewislen blociau `Edrychiad`{:class="block3looks"}.

--- task ---

**Prawf:** Clicia'r corlun **Nano** ar y Llwyfan a gwneud yn siŵr bod swigen siarad yn ymddangos a bod gwisg Nano yn newid.

--- /task ---
