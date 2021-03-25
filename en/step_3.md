## Pico says hello

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
A sprite can have code, costumes, and sounds to change the way that it looks and what it does. 
  
You will add code blocks to make Pico emote with words and sound when the sprite is clicked.
</div>
<div>
![The Pico sprite saying "Hello!"](images/pico-step2.png){:width="300px"}
</div>
</div>

To use blocks, you can click on them in the Blocks menu.

--- task ---

Open the `Looks`{:class="block3looks"} blocks menu. 

Click on a `say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `seconds`{:class="block3looks"} block.

![The 'say Hello! for 2 seconds' block highlighted in yellow](images/pico-say-hello-blocks-menu.png)

The **Pico** sprite will show a speech bubble for two seconds.

![The Pico sprite with "Hello" in a speech bubble](images/pico-say-hello-stage.png)

**Tip:** Code blocks in Scratch glow with a yellow outline when they are running.

--- /task ---

You can drag blocks to the Code area, and they can be used from there.

--- task ---

Drag the `say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `seconds`{:class="block3looks"} block to the Code area. Click on it again.

![Drag code 'say' block to the Code area animated](images/pico-drag-say.gif)

![Drag code 'say' block to the Code area](images/pico-drag-say.png)

--- /task ---

Blocks can be connected together in the Code area to run more than one at a time. Connected blocks will run in order from top to bottom.

--- task ---

Drag a `when this sprite clicked`{:class="block3events"} block from the `Events`{:class="block3events"} blocks menu and connect it to the top of your `say`{:class="block3looks"} block in the Code area. The blocks will snap together.

![Animation of blocks snapping together](images/pico-snap-together.gif)

![The Pico sprite](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] secs // hide after 2 seconds
```

--- /task ---
  
A comment is an explanation of what your code does.
  
```blocks3
say [Hello!] for [2] secs // hide after 2 seconds
```
You will see comments in code examples. You don't need to add the comments when you add code to your project. (But if you have time at the end, it is a good idea to add comments to your code so that it is easier to understand later.)

--- task ---

**Test:** Click on the **Pico** sprite on the Stage to see the speech bubble show for two seconds. It is important to test your code to make sure that it does what you expect.

--- /task ---

--- save ---
