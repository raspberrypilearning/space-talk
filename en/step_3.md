## Pico plays a sound

--- task ---
Can you find a sprite?

--- /task ---

<mark>Need to update - think it's better to use `play sound until done`?</mark>

Delete Scratch sprite
Select 'Choose a sprite' and pick the 'Fantasy' category. Click on the Pico sprite to add it to your project.
Drag to the left side of the stage position 
Your stage should look something like this:


Open the `Sound` blocks menu. Click on a `play sound (pop v) until done` block.
[screenshot][stage Screenshot] 
You should hear a 'pop' sound.

<mark>troubleshoot sound here?</mark>

There are some fantastic alien sounds in Scratch. 
[image]
To choose a new sound click on the 'Choose a sound' button and select the 'space' category. 
[image]
Play a few different sounds using  the play buttons. Once you have found the one you want to use click on it to add it to your project. 

Click back on the Code tab and from the `Sound` blocks menu find the `play sound until done` block. Drag the block into the Code area. Click it to hear your sound. 

Check that your `play sound until done` block has your chosen sound in it. If it doesn’t you’ll need to click on `[pop v]` then select your sound from the menu.

Drag a `when this sprite clicked` block from the Events block menu and connect it to the top of your `play sound until done` block in the Code area. The blocks will snap together.

```blocks3
+when this sprite clicked
play sound [Alien Creak1 v] until done
```
[screenshot and animated gif]

Get the Pico sprite to also say Hello when you click on it:

```blocks3
when this sprite clicked
+say [Hello!]
play sound [Alien Creak1 v] until done
```

Add another `say [Hello!]` block. Click in the 'Hello!' box and delete 'Hello!'. 


```blocks3
when this sprite clicked
say [Hello!]
play sound [Alien Creak1 v] until done
+ say [] // hide speech bubble
```
 
Test: Click on Pico on the stage to see the speech bubble and hear the sound. If you don’t hear the sound make sure you have added the `play sound [Alien Creak1 v] until done` block under `when this sprite clicked`. Also check that sound is working in your computer or tablet. 

[image]

--- save ---
