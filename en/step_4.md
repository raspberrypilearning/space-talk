## Nano switches costume

Sprites have costumes to change the way they look.
  
Add the Nano sprite to your project. 
Click on the Costumes tab to see Nano’s costumes. 
[image]
Go back to the Code tab and drag a `switch costume to` block to the Code area
Try changing the selected costume by clicking on 'nano-a' and choosing another costume from the menu. Then click on the block to see Nano’s costume change on the stage.
You can also change costumes with the Paint editor. You are going to make a costume with one hand up to Nano’s mouth. Click back on the Costumes tab.
Right click on the 'nano-a' costume and choose 'duplicate'. You will have a 'nano-a2' costume.
Click on the arm on the left and then click 'Delete'. The costume should look like this:
[image]
*Tip*: If you make a mistake in the Paint editor you can click Undo [image] 
Click on the 'nano-c' costume. 
Click on the arm on the left.
[image]
Click on 'copy''
[Image]
Switch to costume 'nano-a2' and click on 'Paste'. 
The costume should look like this:
[image]
Now switch to the Code tab and change your code to make Nano say 'thanks!':

```blocks3
when this sprite clicked
say [Thanks!] // show speech bubble
switch costume to [nano-a2 v] // hand to mouth
wait [1] secs // so you see the change
switch costume to [nano-a v] // smiling
say [] // hide the speech bubble
```

*Tip*: All the blocks are colour coded so you will find the `change costume to` block in the `Looks` blocks menu.


Boxout 
[Over 100,000 people use the language 'Makaton' to communicate using signs and symbols. You have just coded Nano to use the Makaton sign for 'thank you.' Next time you say thank you to someone why not use your new skill to say it in Makaton.]


--- save ---
