## Pico ಧ್ವನಿಯನ್ನು ನುಡಿಸುತ್ತಾನೆ

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
ಸಂವಹನ ಮಾಡುವ ಇನ್ನೊಂದು ವಿಧಾನವೆಂದರೆ ಧ್ವನಿಯನ್ನು ಬಳಸುವುದು.
</div>
<div>

![Pico ಸ್ಪ್ರೈಟ್ "Hello!" ಹೇಳುತ್ತಿರುವುದು]‌(images/pico-step2.png){:width="300px"}

</div>
</div>

### Add a sound to the Pico Sprite

--- task ---

**Pico** ಸ್ಪ್ರೈಟ್‌ಗೆ **Sounds** ಟ್ಯಾಬ್‌ ಮೇಲೆ ಕ್ಲಿಕ್‌ ಮಾಡಿ ಮತ್ತು ನೀವು **pop** ಧ್ವನಿಯನ್ನು ಕಾಣಬಹುದು. **pop** ಧ್ವನಿಯನ್ನು ಕೇಳಿಸಿಕೊಳ್ಳಲು **Play** ಐಕಾನ್‌ ಮೇಲೆ ಕ್ಲಿಕ್‌ ಮಾಡಿ.

![Sounds ಟ್ಯಾಬ್‌ನಲ್ಲಿ pop ಧ್ವನಿಯನ್ನು ನುಡಿಸುವುದು.](images/pico-sound-play.png)

**Debug**: If you cannot hear a sound then check that sound is working on your computer or tablet.

--- /task ---

--- task ---

ಹೊಸ ಶಬ್ದವನ್ನು ಆಯ್ಕೆ ಮಾಡಲು, **Choose a Sound** ಐಕಾನ್‌ ಮೇಲೆ ಕ್ಲಿಕ್‌ ಮಾಡಿ ಮತ್ತು **Space** ವರ್ಗವನ್ನು ಆಯ್ಕೆಮಾಡಿಕೊಳ್ಳಿ ಅಥವಾ ಸರ್ಚ್‌ ಬಾಕ್ಸ್‌ನಲ್ಲಿ `space` ಟೈಪ್‌ ಮಾಡಿ.

!['Choose a Sound' ಐಕಾನ್.](images/sound-button.png)

!['Choose a Sound' ಹೈಲೈಟ್‌ ಮಾಡಿರುವ Scratch ಎಡಿಟರ್‌.](images/pico-choose-sound.png)

![Sound Library ಯಲ್ಲಿ 'Space' ವರ್ಗ.](images/pico-space-category.png)

--- /task ---

--- task ---

Play a few different sounds using the **Play** icons. Once you have found the sound that you want to use, click on it to add it to your project.

![ಉದಾಹರಣೆಗೆ Sounds ಟ್ಯಾಬ್‌ನಲ್ಲಿ pop ಧ್ವನಿಯಡಿಯಲ್ಲಿ ತೋರಿಸಿರುವ (Alien Creak1) ಧ್ವನಿ.](images/pico-inserted-sound.png)

--- /task ---

### Make the sound play when clicked (or tapped)

--- task ---

Click on the **Code** tab. In the `Sound`{:class="block3sound"} blocks menu, find the `start sound`{:class="block3sound"} block.

Drag the block into the Code area, between the `when this sprite clicked`{:class="block3events"} block and the `say`{:class="block3looks"} block. A gap will open up and the block will snap into place.

![ಎರಡು ಬ್ಲಾಕ್‌ಗಳ ನಡುವೆ 'start sound' ಬ್ಲಾಕ್‌ ಸೇರಿಸಲಾಗಿದೆ.](images/pico-insert-block.gif)

ನಿಮ್ಮ ಕೋಡ್ ಈ ರೀತಿ ಇರಬೇಕು:

![Pico ಸ್ಪ್ರೈಟ್.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Test your code

--- task ---

Check that your `start sound`{:class="block3sound"} block has your chosen sound in it. If it does not, you need to click on the sound in the `start sound`{:class="block3sound"} block, then select your chosen sound in the drop-down menu.

!['start sound'‌ ಬ್ಲಾಕ್‌ ಒಳಗೆ ಡ್ರಾಪ್‌-ಡೌನ್‌ ಮೆನುನಲ್ಲಿ Alien Creak1 ಧ್ವನಿಯ ಮೇಲೆ ಕ್ಲಿಕ್‌ ಮಾಡುವುದು.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Test:** Click on the **Pico** sprite and check that the speech bubble appears and you can hear the sound. If you do not hear the sound, make sure that you have added the `start sound`{:class="block3sound"} block under the `when this sprite clicked`{:class="block3events"} block.

--- /task ---

