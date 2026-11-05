## Pico yn chwarae sain

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Ffordd arall o gyfathrebu yw defnyddio sain.
</div>
<div>

![Corlun Pico yn dweud, "Helo!"](images/pico-step2.png){:width="300px"}

</div>
</div>

### Add a sound to the Pico Sprite

--- task ---

Clicia'r tab **Seiniau** ar gyfer y corlun **Pico** ac fe weli di sain **pop**. Clicia'r eicon **Chwarae** i glywed y sain **pop**.

![Chwarae'r sain pop yn y tab Seiniau.](images/pico-sound-play.png)

**Debug**: If you cannot hear a sound then check that sound is working on your computer or tablet.

--- /task ---

--- task ---

I ddewis sain newydd, clicia'r eicon **Dewis Sain** a dewis y categori **Gofod** neu deipio `space` yn y blwch chwilio.

![Eicon 'Dewis Sain'.](images/sound-button.png)

![Y golygydd Scratch gyda 'Dewis Sain' wedi'i amlygu.](images/pico-choose-sound.png)

![Categori 'Gofod' yn y Llyfrgell Seiniau.](images/pico-space-category.png)

--- /task ---

--- task ---

Play a few different sounds using the **Play** icons. Once you have found the sound that you want to use, click on it to add it to your project.

![Sain enghreifftiol (sain Alien Creak1) yn ymddangos o dan y sain pop yn y tab Seiniau.](images/pico-inserted-sound.png)

--- /task ---

### Make the sound play when clicked (or tapped)

--- task ---

Click on the **Code** tab. In the `Sound`{:class="block3sound"} blocks menu, find the `start sound`{:class="block3sound"} block.

Drag the block into the Code area, between the `when this sprite clicked`{:class="block3events"} block and the `say`{:class="block3looks"} block. A gap will open up and the block will snap into place.

![Ychwanegu'r bloc 'cychwyn sain' rhwng y ddau floc.](images/pico-insert-block.gif)

Dylai dy god edrych fel hyn:

![Corlun Pico.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Test your code

--- task ---

Check that your `start sound`{:class="block3sound"} block has your chosen sound in it. If it does not, you need to click on the sound in the `start sound`{:class="block3sound"} block, then select your chosen sound in the drop-down menu.

![Clicio ar y sain 'Alien Creak1' yn y gwymplen o fewn y bloc 'cychwyn sain'.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Test:** Click on the **Pico** sprite and check that the speech bubble appears and you can hear the sound. If you do not hear the sound, make sure that you have added the `start sound`{:class="block3sound"} block under the `when this sprite clicked`{:class="block3events"} block.

--- /task ---

