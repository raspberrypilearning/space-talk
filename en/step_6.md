## Giga changes colour

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Sprites can also use thought bubbles and change colours to show their personality. You will get Giga to do this.
</div>
<div>

![The Giga sprite thinking, "Hmm...".](images/giga-step2.png){:width="300px"}

</div>
</div>

--- task ---

Add the **Giga** sprite. 

Drag the **Giga** sprite to the right-hand side of the Stage.

--- /task ---

--- task ---

Make sure that you have the **Giga** sprite selected in the Sprite list below the Stage. Add this code to make the **Giga** sprite communicate by changing colour:

![The Giga sprite.](images/giga-sprite.png)

```blocks3
when this sprite clicked
set [color v] effect to [0] // 0 is the starting colour
think [Hmm...] for [2] seconds 
clear graphic effects // back to the starting colour
```

--- /task ---

**Tip:** Click on the sprite in the Sprite list below the Stage before you add or change code, costumes, or sound. Make sure that you have clicked on the correct sprite.

--- task ---

Try different numbers from `1` to `200` in the `set color effect to`{:class="block3looks"} block until you find a colour that you like. 

--- /task ---

--- task ---

Change the words and number of seconds in the `think`{:class="block3looks"} block.

--- /task ---

--- task ---

**Test:** Click on the **Giga** sprite on the Stage and check that the sprite changes colour and shows a thought bubble.

--- /task ---

--- save ---
