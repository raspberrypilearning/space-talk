## Pico हेलो म्हणतो

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Sprite ला कोड, कॉश्चुम, आणि साऊंड ते कसे दिसतात आणि ते काय करतात हे बदलण्यासाठी ते असू शकतात. 
  
Sprite ला कोड, कॉश्चुम, आणि साऊंड ते कसे दिसतात आणि ते काय करतात हे बदलण्यासाठी ते असू शकतात. 
  
sprite क्लिक केल्यावर शब्द आणि साऊंड यांसह Pico emote तयार करण्यासाठी तुम्ही कोड ठोकळे समाविष्ट कराल.
</div>
<div>

![Pico sprite म्हणत आहे, "हेलो!"](images/pico-step2.png){:width="300px"}

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Emotes**</span> are a way of showing the personality of a character in a game. They can use speech, sounds, movement, and graphic effects, just like in Scratch. Do you play any games that use emotes?
</p>

### Use the say block

--- task ---

`Looks`{:class="block3looks"} ब्लॉक्स मेनू उघडा.

`say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `seconds`{:class="block3looks"} ब्लॉकवर क्लिक करा.

![The 'say Hello! for 2 seconds' block glowing with a yellow outline.](images/pico-say-hello-blocks-menu.png)

**Pico** sprite दोन सेकंदांसाठी स्पीच बबल दाखवेल.

!["हॅलो सह Pico sprite!" स्पीच बबल मध्ये.](images/pico-say-hello-stage.png)

**टीप:** Scratch मधील कोड ब्लॉक्स ते रन होत असतांना पिवळ्या आऊटलाईनसह ग्लो होतात.

--- /task ---

--- task ---

Drag the `say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `seconds`{:class="block3looks"} block to the Code area. Click on it again.

![Dragging the 'say' block to the Code area and clicking on it to run it.](images/pico-drag-say.gif)

![The 'say' block has been dragged to the Code area. The code block glows with a yellow outline.](images/pico-drag-say.png)

--- /task ---

### Make Pico talk when clicked (or tapped)

--- task ---

Drag a `when this sprite clicked`{:class="block3events"} block from the `Events`{:class="block3events"} blocks menu and connect it to the top of your `say`{:class="block3looks"} block in the Code area. The blocks will snap together.

![An animation of the blocks snapping together. When Pico is clicked on, they say "Hello!" for two seconds.](images/pico-snap-together.gif)

![The Pico sprite.](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Code comments

```blocks3
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
You will see comments in code examples. You don't need to add the comments when you add code to your project.

If you have time when you have finished your project, it is a good idea to add comments to your code so that it is easier to understand later. To add a comment, right-click (or on a tablet, tap and hold) on a block in the Code area and choose **Add Comment**.

![The pop-up menu that appears when you right-click on a block. 'Add Comment' is selected.](images/add-comment.png)

### Test

--- task ---

**Test:** Click on the **Pico** sprite on the Stage and check that the speech bubble appears for two seconds. It is important to test your code to make sure that it does what you expect.

--- /task ---

--- task ---

You have already saved your project and given it a name. Scratch will now **automatically** save for you.

You can still click save if you like, just to make sure.

--- /task ---
