## Nano switches costume

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Get Nano to emote by switching **costumes**.

स्प्राइट्स के पास **कॉस्टयूम** होते हैं जो उनके दिखने के तरीके को बदल देते हैं। To animate a sprite, you can change its costume.

</div>
<div>

![Nano बोले, "Thanks"!](images/nano-step2.png){:width="300px"}

</div>
</div>

### Nano signs "Thanks!"

--- task ---

**Fantasy** श्रेणी से अपने प्रोजेक्ट में **Nano** स्प्राइट को डालें।

!['Choose a Sprite' आइकॉन](images/choose-sprite-menu.png)

--- /task ---

--- task ---

सुनिश्चित करें कि Stage के नीचे Sprite सूची में **Nano** का चयन किया गया है।

![Sprite लिस्ट, जिसमे nano स्प्राइट के चारों ओर नीले रंग की आउटलाइन यह दर्शाती है कि Nano का चयन किया गया है।](images/nano-selected.png)


Click on the **Code** tab and add a script to get the **Nano** sprite to sign 'Thanks' using `switch costume to`{:class="block3looks"} and `wait`{:class="block3control"}:

![Nano स्प्राइट।](images/nano-sprite.png)

```blocks3
when this sprite clicked // when Nano is clicked
switch costume to [nano-b v] // Nano talking
wait (0.5) seconds // try 0.25 instead of 0.5
switch costume to [nano-a v] // Nano smiling
```
--- /task ---

**Tip:** All the blocks are colour-coded, so you will find the `switch costume to`{:class="block3looks"} block in the `Looks`{:class="block3looks"} blocks menu and the `wait`{:class="block3control"} block in the `Control`{:class="block3control"} blocks menu.

--- task ---

**Test:** Click on the **Nano** sprite on the Stage and check that Nano's costume changes.

--- /task ---

### Nano साइन भाषा (संकेत भाषा) का उपयोग करता है

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">लाखों लोग बातचीत करने के लिए साइन भाषा का उपयोग करते हैं। A common way to sign 'Thank you' is to place your fingers on your chin with your hand as flat as possible. You then move your hand forwards, away from your chin and slightly down. 
</p>

<!-- Add a video of someone signing -->

Nano कास्ट्यूम बदलकर साइन भाषा का प्रयोग करेगा।

आप Paint एडिटर के साथ अपने स्प्राइट्स के लिए कोस्टयूम एडिट कर सकते हैं। आप Nano का एक कोस्टयूम एडिट करके उनसे साइन भाषा में "thank you" बुलवाएंगे।

--- task ---

**Nano** स्प्राइट के कास्ट्यूम देखने के लिए **Costumes** टैब पर क्लिक करें:

![Nano स्प्राइट के लिए उपलब्ध कास्ट्यूम ।](images/nano-costumes.png)

--- /task ---

--- task ---

**nano-b** कास्ट्यूम पर क्लिक करें। बाएं हाथ की ओर की बाँह पर क्लिक करें फिर **Delete**पर क्लिक करें।

![चुने गए हाथ के साथ nano-b कास्ट्यूम ।](images/nano-arm-selected.png)

आपकी कास्ट्यूम (पोशाक) इस तरह दिखनी चाहिए:

![हटाई हुई बाँह के साथ nano-b कास्ट्यूम।](images/nano-arm-deleted.png)

--- /task ---

**सलाह:** यदि आप Paint एडिटर में कोई गलती करते हैं, तो आप **Undo**पर क्लिक कर सकते हैं।

!['Undo' आइकन।](images/nano-undo.png)

--- task ---

**nano-c** कॉस्ट्यूम पर जाएं और बाएं हाथ की ओर बांह पर क्लिक करें, फिर **Copy**पर क्लिक करें।

![चुनी गयी बाँह के साथ nano-c कास्ट्यूम।](images/nano-c-arm-selected.png)

--- /task ---

--- task ---

**nano-b** कास्ट्यूम पर वापस जाएं और **Paste** पर क्लिक करें। कास्ट्यूम इस तरह दिखना चाहिए:

![nano-c कास्ट्यूम की बाँह के साथ nano-b कास्ट्यूम।](images/nano-b-new-arm.png)

--- /task ---

--- task ---

**Test:** स्टेज पर स्प्राइट में **Nano** पर क्लिक करें और जांचें कि स्पीच बबल दिखाई देता है और Nano का कास्ट्यूम आपके द्वारा एडिट करे गए कास्ट्यूम में बदल जाता है।

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">आपने "thank you" इशारा करना सीख लिया है। अगली बार जब आप किसी को धन्यवाद दें, तो क्यों न अपने नए कौशल का उपयोग करें?
</p>

