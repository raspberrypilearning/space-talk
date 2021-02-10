## Pico plays a sound

--- task ---
Can you find a sprite in your project? That's Scratch the cat. 

Delete the cat sprite by ...

--- /task ---

--- task ---
Select 'Choose a sprite' and pick the 'Fantasy category. Click on the Pico sprite to add it to your project.

--- /task ---

--- task ---
Drag Pico to the left side of the stage position. Your stage should look something like this:
![Stage with chosen backdrop and Pico sprite positioned on the left][images/pico-on-stage.png] 
--- /task ---

--- task ---
Open the `Looks` blocks menu. Click on a `say [Hello!] for [2] secs` block.
Pico will show a speech bubble for two seconds. 

--- /task ---

--- task ---
Drag the  `say [Hello!] for [2] secs` block to the Code area. Click on it again. 

![Drag code say block to code area animated][images/drag-say.gif] 
![Drag code say block to code area][images/drag-say.png] 

--- /task ---

--- task ---
Drag a `when this sprite clicked` block from the `Events` block menu and connect it to the top of your `say [Hello!] for [2] secs` block in the Code area. The blocks will snap together.

```blocks3
+when this sprite clicked
say [Hello!] for [2] secs // hide after 2 seconds
```

--- /task ---

--- task ---
Test: Test your code by clicking on Pico on the Stage. 
[image]
--- /task ---

--- task ---
Another way to communicate is to use sound.

Click on the Sounds tab for the Pico sprite and you’ll find a `pop` sound. 
[image]

Click on the play button to see what pop sounds like. You can use this sound in your project but there are some fantastic alien sounds in Scratch too. 
[image]
To choose a new sound click on the 'Choose a sound' button and select the 'Space' category. 
[image]

Play a few different sounds using  the play buttons. Once you have found the one you want to use click on it to add it to your project. 

--- /task ---

--- task ---
Click back on the Code tab and from the 'Sound' blocks menu find the `start sound until` block. Drag the block into the Code area and connect it between the `when this sprite clicked` and `say [Hello!] for [2] secs` blocks. 

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] // don't wait
say [Hello!] for [2] secs // hide after 2 seconds
```

Check that your `start sound` block has your chosen sound in it. If not, you'll need to click on the sound then select your sound from the menu.

--- /task ---

--- task ---

Test: Click on Pico to see the speech bubble and hear the sound. If you don’t hear the sound make sure you have added the `start sound [Alien Creak1 v]` block under `when this sprite clicked`. Also check that sound is working in your computer or tablet. 

--- /task ---

--- save ---
