## Pico साऊंड प्ले करतो

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
संवाद साधण्याचा दुसरा मार्ग म्हणजे साऊंड वापरणे.
</div>
<div>

![Pico sprite म्हणत आहे, "Hello!"](images/pico-step2.png){:width="300px"}

</div>
</div>

### Add a sound to the Pico Sprite

--- task ---

**Pico** sprite साठी **Sounds** टॅबवर क्लिक करा आणि तुम्हाला **pop** साऊंड मिळेल. **pop** साऊंड ऐकण्यासाठी **Play** आयकॉनवर क्लिक करा.

![Sounds टॅबमध्ये पॉप साऊंड प्ले होत आहे.](images/pico-sound-play.png)

**Debug**: If you cannot hear a sound then check that sound is working on your computer or tablet.

--- /task ---

--- task ---

नवीन साऊंड निवडण्यासाठी, **Choose a Sound** आयकॉनवर क्लिक करा आणि **Space** कॅटेगरी निवडा किंवा सर्च बॉक्समध्ये `space` टाईप करा.

!['Choose a Sound' आयकॉन.](images/sound-button.png)

![हायलाईट केलेल्या 'Choose a Sound' सह Scratch एडिटर.](images/pico-choose-sound.png)

![Sound Library मधील 'Space' कॅटेगरी.](images/pico-space-category.png)

--- /task ---

--- task ---

Play a few different sounds using the **Play** icons. Once you have found the sound that you want to use, click on it to add it to your project.

![उदाहरण साऊंड (Alien Creak1 sound) Sounds टॅब मधील पॉप साऊंडच्या खाली दाखवला आहे.](images/pico-inserted-sound.png)

--- /task ---

### Make the sound play when clicked (or tapped)

--- task ---

Click on the **Code** tab. In the `Sound`{:class="block3sound"} blocks menu, find the `start sound`{:class="block3sound"} block.

Drag the block into the Code area, between the `when this sprite clicked`{:class="block3events"} block and the `say`{:class="block3looks"} block. A gap will open up and the block will snap into place.

![दोन ब्लॉक्समध्ये 'start sound' ब्लॉक जोडला जात आहे.](images/pico-insert-block.gif)

आपला कोड असा दिसला पाहिजे:

![Pico sprite.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Test your code

--- task ---

Check that your `start sound`{:class="block3sound"} block has your chosen sound in it. If it does not, you need to click on the sound in the `start sound`{:class="block3sound"} block, then select your chosen sound in the drop-down menu.

!['start sound' ब्लॉकमध्ये ड्रॉप-डाउन मेनूमधील Alien Creak1 ध्वनीवर क्लिक करणे.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Test:** Click on the **Pico** sprite and check that the speech bubble appears and you can hear the sound. If you do not hear the sound, make sure that you have added the `start sound`{:class="block3sound"} block under the `when this sprite clicked`{:class="block3events"} block.

--- /task ---

