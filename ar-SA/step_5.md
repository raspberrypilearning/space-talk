## Nano يبدل المظاهر

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

ستجعل Nano يعبر عن مشاعره عن طريق تبديل مظهره **الهيئة**.

الكائنات تمتلك **المظاهر** لتغيير الطريقة التي تظهر بها. They are usually slightly different images of the same sprite. لتحريك كائن ما، يمكنك تغيير مظهره.

</div>
<div>

![الكائن Nano يقول، "شكراً!"](images/nano-step-2.png){:width="300px"}

</div>
</div>

--- task ---

أضف الكائن **Nano** إلى مشروعك من فئة **عالم الخيال**.

![أيقونة "اختيار كائن".](images/choose-sprite-menu.png)

--- /task ---

--- task ---

تأكد من تحديد الكائن **Nano** في قائمة الكائن أسفل المنصة.

![قائمة الكائن، مع أطار أزرق حول الكائن Nano لإظهار أنه تم أختيار Nano.](images/nano-selected.png)

أنقر على تبويب **المقاطع البرمجية** وأضف نص للحصول على الكائن **Nano** `لقول`{:class="block3looks"}`شكراً!`: Use the drop down menu to switch between `nano-b`{:class="block3looks"} and `nano-a`{:class="block3looks"}:

![الكائن Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // عندما يتم النقر فوق Nano
switch costume to [nano-b v] // Nano يتحدث
say [شكرا!] for [2] seconds // جرب 1 بدلاً من 2
switch costume to [nano-a v] // Nano يبتسم
```
--- /task ---

**نصيحة:** جميع الكتل البرمجية مميزة بالألوان، لذلك ستجد كتلة`غير المظهر الى `في قائمة الكتل`الهيئة`{:class="block3looks"} وستجد كتلة `انتظر` في قائمة الكتل`التحكم`{:class="block3control"} blocks menu.

--- task ---

**اختبار:** انقر فوق **Nano** sprite على المنصة وتأكد من أن مظهر Nano قد تغير.

--- /task ---
