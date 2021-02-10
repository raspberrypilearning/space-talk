## Pico plays a sound

--- task ---
Open the `Looks`{:class="block3looks"} blocks menu. Click on a `say [Hello!] for [2] secs`{:class="block3looks"} block.

![Clicking on say hello in Looks block menu](images/say-hello.png)

Pico will show a speech bubble for two seconds. 

![Pico with hello in speech bubble](images/say-hello-stage.png)

--- /task ---

--- task ---
Drag the  `say [Hello!] for [2] secs`{:class="block3looks"} block to the Code area. Click on it again. 

![Drag code say block to code area animated][images/drag-say.gif] 

![Drag code say block to code area][images/drag-say.png] 

--- /task ---

--- task ---
Drag a `when this sprite clicked`{:class="block3events"} block from the `Events`{:class="block3events"} block menu and connect it to the top of your `say [Hello!] for [2] secs`{:class="block3looks"} block in the Code area. The blocks will snap together.

![Animation of blocks snapping together](images/snap-together.png)

![image of Pico sprite](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] secs // hide after 2 seconds
```

--- /task ---

--- task ---
Test: Test your code by clicking on Pico on the Stage. 
--- /task ---

--- task ---
Another way to communicate is to use sound.

Click on the Sounds tab for the Pico sprite and you’ll find a 'pop' sound. 

![Sound editor](images/sound-editor.png)

Click on the 'play' button to hear the pop sound. You can use this sound in your project but there are some fantastic alien sounds in Scratch too. 

To choose a new sound click on the 'Choose a sound' button and select the 'Space' category. 

![Choose sound menu](images/choose-sound.png)

![Space category](images/space-category.png)

Play a few different sounds using  the play buttons. Once you have found the one you want to use click on it to add it to your project. 

--- /task ---

--- task ---
Click back on the Code tab and from the `Sound`{:class="block3sound"} blocks menu find the `start sound`{:class="block3sound"} block. Drag the block into the Code area and connect it between the `when this sprite clicked`{:class="block3events"} and `say [Hello!] for [2] secs`{:class="block3looks"} blocks. 

![image of Pico sprite](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v]
say [Hello!] for [2] secs // hide after 2 seconds
```

Check that your `start sound`{:class="block3sound"} block has your chosen sound in it. If not, you'll need to click on the sound then select your sound from the menu.

--- /task ---

--- task ---

Test: Click on Pico to see the speech bubble and hear the sound. If you don’t hear the sound make sure you have added the `start sound [Alien Creak1 v]`{:class="block3sound"} block under `when this sprite clicked`{:class="block3events"}. Also check that sound is working in your computer or tablet. 

--- /task ---

--- save ---
