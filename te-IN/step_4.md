## Pico ధ్వనిని ప్లే చేస్తుంది

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
కమ్యూనికేట్ చేయడానికి మరొక మార్గం ధ్వనిని ఉపయోగించడం.
</div>
<div>

![Pico sprite చెప్తోంది, "Hello!"](images/pico-step2.png){:width="300px"}

</div>
</div>

### Add a sound to the Pico Sprite

--- task ---

**Pico** sprite కోసం **Sounds** ట్యాబ్‌పై క్లిక్ చేయండి మరియు మీరు **pop** సౌండ్‌ను కనుగొంటారు. **pop** సౌండ్ వినడానికి **Play** చిహ్నంపై క్లిక్ చేయండి.

![Sounds ట్యాబ్‌లో pop sound ప్లే అవుతోంది.](images/pico-sound-play.png)

**Debug**: If you cannot hear a sound then check that sound is working on your computer or tablet.

--- /task ---

--- task ---

కొత్త ధ్వనిని ఎంచుకోవడానికి, **Choose a Sound** చిహ్నంపై క్లిక్ చేసి, **Space** వర్గాన్ని ఎంచుకోండి లేదా సెర్చ్ బాక్సులో `space` అని టైప్ చేయండి.

!['Choose a Sound' చిహ్నం.](images/sound-button.png)

!['Choose a Sound'తో గల Scratch ఎడిటర్, హైలైట్ చేయబడింది.](images/pico-choose-sound.png)

![Sound లైబ్రరీలో కల 'Space' వర్గం.](images/pico-space-category.png)

--- /task ---

--- task ---

Play a few different sounds using the **Play** icons. Once you have found the sound that you want to use, click on it to add it to your project.

![Sounds ట్యాబ్‌లోని pop sound క్రింద కల ధ్వని, (Alien Creak1) ఉదాహరణగా చూపబడినది.](images/pico-inserted-sound.png)

--- /task ---

### Make the sound play when clicked (or tapped)

--- task ---

Click on the **Code** tab. In the `Sound`{:class="block3sound"} blocks menu, find the `start sound`{:class="block3sound"} block.

Drag the block into the Code area, between the `when this sprite clicked`{:class="block3events"} block and the `say`{:class="block3looks"} block. A gap will open up and the block will snap into place.

![రెండు బ్లాక్‌ల మధ్య 'start sound' బ్లాక్ జోడించబడుతోంది.](images/pico-insert-block.gif)

మీ ప్రాజెక్ట్ ఇలా కనిపించాలి:

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

!['start sound' బ్లాక్‌లోని డ్రాప్-డౌన్ మెనులో Alien Creak1 ధ్వని పై క్లిక్ చేయడం.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Test:** Click on the **Pico** sprite and check that the speech bubble appears and you can hear the sound. If you do not hear the sound, make sure that you have added the `start sound`{:class="block3sound"} block under the `when this sprite clicked`{:class="block3events"} block.

--- /task ---

