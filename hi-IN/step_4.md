## Pico ने बजायी एक ध्वनि

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
बातचीत करने का दूसरा तरीका ध्वनि का उपयोग करना है।
</div>
<div>

![Pico स्प्राइट बोले, "हेलो" (Hello)!](images/pico-step2.png){:width="300px"}

</div>
</div>

--- task ---

**Pico** स्प्राइट के लिए **Sounds** टैब पर क्लिक करें और वहां आपको **pop** ध्वनि मिलेगी। **Pop** ध्वनि सुनने के लिए **Play** आइकन पर क्लिक करें।

![Sounds टैब में pop ध्वनि बजाना।](images/pico-sound-play.png)

--- /task ---

Scratch में कुछ शानदार अपर देशीय ध्वनियाँ हैं जिन्हें आप अपने स्प्राइट में जोड़ सकते हैं।

--- task ---

एक नई ध्वनि चुनने के लिए, **Choose a Sound** आइकन पर क्लिक करें और **space** श्रेणी चुनें या खोज बॉक्स में `space`लिखें।

!['Choose a Sound' आइकॉन](images/sound-button.png)

![Scratch एडिटर जिसमें 'Choose a Sound' हाइलाइट किया गया है।](images/pico-choose-sound.png)

![Sound Library में 'स्पेस (Space)' श्रेणी।](images/pico-space-category.png)

--- /task ---

--- task ---

**Play** आइकन का उपयोग करके कुछ अलग अलग ध्वनियां बजाएं। एक बार जब आपको वह ध्वनि मिल जाए जिसका आप उपयोग करना चाहते हैं, तो उसे अपने प्रोजेक्ट में जोड़ने के लिए उस पर क्लिक करें।

![Sounds टैब में पॉप ध्वनि के नीचे दिखाई गई एक उदाहरण ध्वनि (Alien Creak1 ध्वनि)।](images/pico-inserted-sound.png)

--- /task ---

--- task ---

**Code** टैब पर क्लिक करें। `Sound`{:class="block3sound"} ब्लॉक मेनू में, `start sound`{:class="block3sound"} ब्लॉक ढूंढें।

ब्लॉक को कोड क्षेत्र में खींचें, `when this sprite clicked`{:class="block3events"} ब्लॉक और `say`{:class="block3looks"} ब्लॉक के बीच में। एक गैप खुल जाएगा और ब्लॉक अपनी जगह पर आ जाएगा।

![दो ब्लॉकस के बीच 'स्टार्ट साउंड (start sound)' ब्लॉक जोड़ा जा रहा है।](images/pico-insert-block.gif)

आपका कोड इस प्रकार दिखना चाहिए:

![Pico स्प्राइट।](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

--- task ---

जांचें कि आपके `start sound`{:class="block3sound"} ब्लॉक में आपकी चुनी हुई ध्वनि है। यदि ऐसा नहीं है, तो आपको `start sound`{:class="block3sound"} ब्लॉक में ध्वनि पर क्लिक करना होगा, फिर ड्रॉप-डाउन मेनू में अपनी चुनी हुई ध्वनि का चयन करना होगा।

!['स्टार्ट साउंड (start sound)' ब्लॉक के भीतर ड्रॉप-डाउन मेनू में Alien Creak 1 ध्वनि पर क्लिक करना।](images/pico-sound-menu.png)

--- /task ---

--- task ---

**परीक्षण:** **Pico** स्प्राइट पर क्लिक करें और जांचें कि स्पीच बबल दिखाई दे रहा है और आपको ध्वनि सुनाई दे रही है। यदि आप ध्वनि नहीं सुनते हैं, तो जांचे कि आपने `start sound`{:class="block3sound"} ब्लॉक को `when this sprite clicked`{:class="block3events"} ब्लॉक के ही नीचे जोड़ा है। साथ ही, जांच लें कि ध्वनि आपके कंप्यूटर या टैबलेट पर काम कर रही है या नहीं।

--- /task ---

--- save ---

