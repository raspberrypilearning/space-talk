## Pico says hello

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
एक स्प्राइट में कोड, कोस्टयूम और ध्वनियां हो सकती हैं जिससे की हम वह कैसा दिखता है या क्या करता है, वह बदल सकते हैं। 
  
You will add code blocks to make Pico emote with words and sound when the sprite is clicked.
</div>
<div>

![Pico sprite बोले, "Hello"!](images/pico-step2.png){:width="300px"}

</div>
</div>

To use blocks, you can click on them in the Blocks menu.

--- task ---

`Looks`{:class="block3looks"} ब्लॉक मेन्यू खोलें।

`say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `seconds`{:class="block3looks"} ब्लॉक पर क्लिक करें।

![The 'say Hello! for 2 seconds' block glowing with a yellow outline.](images/pico-say-hello-blocks-menu.png)

**Pico** स्प्राइट दो सेकंड के लिए स्पीच बबल दिखाएगा।

![Pico स्प्राइट "Hello!" स्पीच बबल में।](images/pico-say-hello-stage.png)

**Tip:** Code blocks in Scratch glow with a yellow outline when they are running.

--- /task ---

You can drag blocks to the Code area, and they can be used from there.

--- task ---

`say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `सेकंड`{:class="block3looks"} ब्लॉक को कोड क्षेत्र में खींचे। उस पर फिर से क्लिक करें।

!['say' ब्लॉक को कोड क्षेत्र में खींचकर इसे चलाने के लिए उस पर क्लिक करें।](images/pico-drag-say.gif)

!['say' ब्लॉक को कोड क्षेत्र में खींच लिया गया है। The code block glows with a yellow outline.](images/pico-drag-say.png)

--- /task ---

Blocks can be connected together in the Code area to run more than one at a time. जुड़े हुए ब्लॉक ऊपर से नीचे के क्रम में चलेंगे।

--- task ---

Drag a `when this sprite clicked`{:class="block3events"} block from the `Events`{:class="block3events"} blocks menu and connect it to the top of your `say`{:class="block3looks"} block in the Code area. ब्लॉक एक साथ चिपक जाएंगे।

![एक साथ जुड़ते हुए ब्लॉकस का एक एनीमेशन। जब Pico पर क्लिक किया जाता है, तो दो सेकंड के लिए वह कहता है "Hello!" ।](images/pico-snap-together.gif)

![Pico स्प्राइट।](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

एक कमेंट विस्तार से बताता है कि आपका कोड क्या करता है।

```blocks3
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
आप कोड उदाहरणों में कमेंट देखेंगे। जब आप अपने प्रोजेक्ट में कोड जोड़ते हैं तो आपको कमेंट को डालने की आवश्यकता नहीं होती है।

यदि आपके पास अपना प्रोजेक्ट पूरा करने करने के बाद समय बचता हैं, तो अपने कोड में कमेंट डालना एक अच्छा विचार है ताकि बाद में इसे समझना आसान हो। To add a comment, right-click (or on a tablet, tap and hold) on a block in the Code area and choose **Add Comment**.

![जब आप किसी ब्लॉक पर राइट-क्लिक करते हैं तो पॉप-अप मेनू दिखाई देता है। 'Add comment' चुना गया है।](images/add-comment.png)

--- task ---

**Test:** Click on the **Pico** sprite on the Stage and check that the speech bubble appears for two seconds. अपने कोड का टेस्ट करना ज़रूरी हैं ताकि आप ये देख सकें की क्या ये वही कर रहा है जैसा आप चाहते हैं।

--- /task ---

--- save ---
