## Giga बदले रंग

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
स्प्राइट्स अपने व्यक्तित्व को दिखाने के लिए स्पीच बबल का उपयोग कर सकते हैं और रंग बदल सकते हैं। आपको Giga से ऐसा करवाना है।
</div>
<div>

![Giga स्प्राइट सोच रहा है, "Hmm..."।](images/giga-step2.png){:width="300px"}

</div>
</div>

### गीगा का रंग बदलें

--- task ---

**Giga** स्प्राइट जोड़ें।

**Giga** स्प्राइट को स्टेज के दाहिने ओर खींचे।

--- /task ---

--- task ---

सुनिश्चित करें कि आपके पास Stage के नीचे Sprite लिस्ट में **Giga** चुना हुआ है। रंग बदलकर **Giga** स्प्राइट से बातचीत करवाने के लिए इस कोड को जोड़ें:

![Giga स्प्राइट.](images/giga-sprite.png)

```blocks3
when this sprite clicked
set [color v] effect to [0] // 0 प्रारंभिक रंग है
think [Hmm...] for [2] seconds 
clear graphic effects // शुरुआती रंग में वापस
```

--- /task ---

**सलाह:** कोड, कास्ट्यूम या ध्वनि जोड़ने या बदलने से पहले Stage के नीचे Sprite लिस्ट में स्प्राइट पर क्लिक करें। सुनिश्चित करें कि आपने सही स्प्राइट पर क्लिक किया है।

--- task ---

`set color effect to`{:class="block3looks"} ब्लॉक में `1` से `200` तक के अलग-अलग अंक आज़माएं, जब तक कि आपको अपनी पसंद का रंग न मिल जाए।

--- /task ---

--- task ---

`think`{:class="block3looks"} ब्लॉक में शब्दों और सेकंडों की संख्या बदलें।

--- /task ---

--- task ---

**परीक्षण:** Stage पर **Giga** स्प्राइट पर क्लिक करें और जांचें कि स्प्राइट रंग बदलता है की नहीं और एक स्पीच बबल दिखाता है।

--- /task ---

