### Pico plays a sound

Another way to communicate is to use sound.

--- task ---

Click on the **Sounds** tab for the **Pico** sprite and you will find a **pop** sound. Click the **Play** button to hear the **pop** sound.

![Selecting the pop sound in the Sound editor](images/pico-sound-play.png)

--- /task ---

There are some fantastic alien sounds in Scratch that you can add to your sprite.

--- task ---

To choose a new sound, click the **Choose a Sound** button and select the **Space** category or type `space` in the search box.

![The 'Choose a Sound' menu](images/sound-button.png)

![The 'Choose a Sound' menu](images/pico-choose-sound.png)

![The 'Space' category](images/pico-space-category.png)

--- /task ---

--- task ---

Play a few different sounds using the **Play** buttons. Once you have found the sound that you want to use, click on it to add it to your project.

![Inserted sound, playing the Animal Creak sound](images/pico-inserted-sound.png)

--- /task ---

--- task ---

Click on the **Code** tab. In the `Sound`{:class="block3sound"} blocks menu, find the `start sound`{:class="block3sound"} block. 

Drag the block into the Code area between the `when this sprite clicked`{:class="block3events"} block and the `say`{:class="block3looks"} block. A gap will open up and the block will snap into place.

![The 'start sound' block being added between two blocks](images/pico-insert-block.gif)

Your code should look like this:

![The Pico sprite](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hello!] for [2] secs // hide after 2 seconds
```

--- /task ---

--- task ---

Check that your `start sound`{:class="block3sound"} block has your chosen sound in it. If it does not, you need to click on the sound in the `start sound`{:class="block3sound"} block then select your chosen sound from the drop-down menu.

![Clicking on your new sound in the sound menu](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Test:** Click on the **Pico** sprite to see the speech bubble and hear the sound. If you do not hear the sound, make sure that you have added the `start sound [Alien Creak1]`{:class="block3sound"} block under the `when this sprite clicked`{:class="block3events"} block. Also, check that the sound is working on your computer or tablet.

--- /task ---

--- save ---

