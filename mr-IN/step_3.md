## Pico हेलो म्हणतो

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Sprite ला कोड, कॉश्चुम, आणि साऊंड ते कसे दिसतात आणि ते काय करतात हे बदलण्यासाठी ते असू शकतात. 
  
You will add code blocks to make Pico emote with words and sound when the sprite is clicked.
</div>
<div>

![The Pico sprite saying, "Hello!"](images/pico-step2.png){:width="300px"}

</div>
</div>

ब्लॉक्सचा वापर करण्यासाठी, तुम्ही Blocks मेनूमधील त्यांच्यावर क्लिक करू शकता.

--- task ---

`Looks`{:class="block3looks"} ब्लॉक्स मेनू उघडा.

`say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `seconds`{:class="block3looks"} ब्लॉकवर क्लिक करा.

![The 'say Hello! for 2 seconds' block glowing with a yellow outline.](images/pico-say-hello-blocks-menu.png)

**Pico** sprite दोन सेकंदांसाठी स्पीच बबल दाखवेल.

!["हॅलो सह Pico sprite!" स्पीच बबल मध्ये.](images/pico-say-hello-stage.png)

**Tip:** Code blocks in Scratch glow with a yellow outline when they are running.

--- /task ---

You can drag blocks to the Code area, and they can be used from there.

--- task ---

`say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `seconds`{:class="block3looks"} हा ब्लॉक कोड एरियाला ड्रॅग करा. त्यावर पुन्हा क्लिक करा.

![Dragging the 'say' block to the Code area and clicking on it to run it.](images/pico-drag-say.gif)

![The 'say' block has been dragged to the Code area. कोड पिवळ्या आऊटलाईनसह ग्लो होतो.](images/pico-drag-say.png)

--- /task ---

Blocks can be connected together in the Code area to run more than one at a time. कनेक्ट केलेले ब्लॉक्स वरतून खालपर्यंतच्या क्रमात रन होतील.

--- task ---

Drag a `when this sprite clicked`{:class="block3events"} block from the `Events`{:class="block3events"} blocks menu and connect it to the top of your `say`{:class="block3looks"} block in the Code area. ब्लॉक्स एकत्र स्नॅप होतील.

![ब्लॉक्सचे ऍनिमेशन एकत्रितपणे स्नॅप होत आहे. When Pico is clicked on, they say "Hello!" for two seconds.](images/pico-snap-together.gif)

![Pico sprite.](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

कमेंट म्हणजे तुमचा कोड काय करतो याबद्दलचे स्पष्टीकरण.

```blocks3
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
तुम्हाला कोड उदाहरणांमध्ये टिप्पण्या दिसतील. तुम्ही तुमच्या प्रोजेक्टमध्ये कोड जोडता तेव्हा तुम्हाला टिप्पण्या जोडण्याची गरज नाही.

तुम्ही तुमचा प्रोजेक्ट पूर्ण केल्यावर तुमच्याकडे वेळ असल्यास, तुमच्या कोडमध्ये कमेंट जोडणे चांगली कल्पना आहे जेणेकरून नंतर समजणे सोपे होईल. To add a comment, right-click (or on a tablet, tap and hold) on a block in the Code area and choose **Add Comment**.

![तुम्ही ब्लॉकवर राईट-क्लिक केल्यावर दिसणारा पॉप-अप मेनू. 'Add Comment' निवडले आहे.](images/add-comment.png)

--- task ---

**Test:** Click on the **Pico** sprite on the Stage and check that the speech bubble appears for two seconds. तुमचा कोड तुमच्या अपेक्षेप्रमाणे कार्य करतो का याची खात्री करण्यासाठी तुमच्या कोडची चाचणी घेणे महत्त्वाचे आहे.

--- /task ---

--- save ---
