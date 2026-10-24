## Nano ಉಡುಪುಗಳನ್ನು ಬದಲಾಯಿಸುತ್ತದೆ

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Get Nano to emote by switching **costumes**.

ಸ್ಪ್ರೈಟ್‌ಗಳಿಗೆ ಅವುಗಳು ಯಾವ ರೀತಿ ಕಾಣುತ್ತವೆ ಎಂಬುವುದನ್ನು ಬದಲಾಯಿಸಲು **costumes** ಇವೆ. They are usually slightly different images of the same sprite. To animate a sprite, you can change its costume.

</div>
<div>

![Nano ಸ್ಪ್ರೈಟ್‌, "Thanks!"ಹೇಳುತ್ತಿರುವುದು](images/nano-step-2.png){:width="300px"}

</div>
</div>

--- task ---

ನಿಮ್ಮ ಪ್ರಾಜೆಕ್ಟ್‌ಗೆ **Fantasy** ವರ್ಗದಿಂದ **Nano** ಸ್ಪ್ರೈಟ್‌ ಸೇರಿಸಿ.

!['Choose a Sprite' ಐಕಾನ್.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Stage ಕೆಳಗೆ Sprite ಲಿಸ್ಟ್‌ನಲ್ಲಿ **Nano** ಸ್ಪ್ರೈಟ್‌ ಆಯ್ಕೆ ಮಾಡಿರುವುದನ್ನು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಿ.

![Nano ಆಯ್ಕೆಯಾಗಿದೆ ಎಂದು ತೋರಿಸಲು Nano ಸ್ಪ್ರೈಟ್ ಸುತ್ತಲೂ ನೀಲಿ ಅಂಚು ಹೊಂದಿರುವ ಸ್ಪ್ರೈಟ್ ಲಿಸ್ಟ್.](images/nano-selected.png)

Click on the **Code** tab and add a script to get the **Nano** sprite to change costume using `switch costume to`{:class="block3looks"} and `wait`{:class="block3control"}. Use the drop down menu to switch between `nano-b`{:class="block3looks"} and `nano-a`{:class="block3looks"}:

![Nano ಸ್ಪ್ರೈಟ್.](images/nano-sprite.png)

```blocks3
when this sprite clicked // Nano ಕ್ಲಿಕ್‌ ಮಾಡಿದಾಗ
switch costume to [nano-b v] // Nano ಮಾತನಾಡುತ್ತಿರುವುದು
say [Thanks!] for [2] seconds // 2ರ ಬದಲು 1 ಪ್ರಯತ್ನಿಸಿ
switch costume to [nano-a v] // Nano ನಗುತ್ತಿರುವುದು
```
--- /task ---

**ಸಲಹೆ:** ಎಲ್ಲಾ ಬ್ಲಾಕ್‌ಗಳಿಗೆ ಬಣ್ಣಗಳನ್ನು ಕೊಡಲಾಗಿದೆ, ಆದುದರಿಂದ ನೀವು `switch costume to`{:class="block3looks"} ಬ್ಲಾಕ್‌ನ್ನು `Looks`{:class="block3looks"} ಬ್ಲಾಕ್‌ಗಳ ಮೆನುನಲ್ಲಿ ನೋಡುವಿರಿ.

--- task ---

**ಪರೀಕ್ಷೆ:** Stage ಮೇಲಿನ **Nano** ಸ್ಪ್ರೈಟ್‌ ಮೇಲೆ ಕ್ಲಿಕ್‌ ಮಾಡಿ ಮತ್ತು ಮಾತಿನ ಗುಳ್ಳೆ ಕಾಣುತ್ತದೆ ಮತ್ತು Nanoನ ಉಡುಪು ಬದಲಾಗುವುದನ್ನು ಪರಿಸೀಲಿಸಿ.

--- /task ---
