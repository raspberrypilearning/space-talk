## Nano ने कॉश्चुम बदलला

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Get Nano to emote by switching **costumes**.

स्प्राईटकडे त्यांना हवा तो बदल करण्यासाठी **कॉश्चुम** आहे. They are usually slightly different images of the same sprite. To animate a sprite, you can change its costume.

</div>
<div>

![Nano स्प्राईट म्हणतो, "Thanks!"](images/nano-step-2.png){:width="300px"}

</div>
</div>

--- task ---

**Fantasy** कॅटेगरी मधून तुमच्या प्रोजेक्टला **Nano** स्प्राईट जोडा.

!["Choose a Sprite" आयकॉन.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Stage च्या खालील Sprite यादीमध्ये **Nano** स्प्राईट निवडला असल्याची खात्री करा.

![Nano निवडला हे दाखवण्यासाठी Nano स्प्राईट भोवती निळ्या बॉर्डरसह Sprite लीस्ट.](images/nano-selected.png)

Click on the **Code** tab and add a script to get the **Nano** sprite to change costume using `switch costume to`{:class="block3looks"} and `wait`{:class="block3control"}. Use the drop down menu to switch between `nano-b`{:class="block3looks"} and `nano-a`{:class="block3looks"}:

![Nano स्प्राईट.](images/nano-sprite.png)

```blocks3
when this sprite clicked // Nano वर जेव्हा क्लिक केले जाते
switch costume to [nano-b v] // Nano टॉकींग
say [Thanks!] for [2] seconds // 2 ऐवजी 1 चा प्रयत्न करा
switch costume to [nano-a v] // Nano स्माइलिंग
```
--- /task ---

**टीप:** सर्व ब्लॉक्स कलर-कोडेड आहेत, त्यामुळे तुम्हाला `switch costume to`{:class="block3looks"} हा ब्लॉक `Looks`{:class="block3looks"} ब्लॉक मेनूमध्ये आढळेल.

--- task ---

**चाचणी:** Stage वरील **Nano** स्प्राईटवर क्लिक करा आणि स्पीच बबल दिसतो का आणि Nano चा कॉश्चुम बदलतो का ते तपासा.

--- /task ---
