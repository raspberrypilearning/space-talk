## Nano يبدل المظاهر

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

ستجعل Nano يعبر عن مشاعره عن طريق تبديل مظهره ** الهيئة**.

الكائنات تمتلك **المظاهر** لتغيير الطريقة التي تظهر بها. لتحريك كائن ما، يمكنك تغيير مظهره.

</div>
<div>

![الكائن Nano يقول، "شكراً!"](images/nano-step-2.png){:width="300px"}

</div>
</div>

### Nano يقول "شكرًا!"

--- task ---

أضف الكائن **Nano** إلى مشروعك من فئة **عالم الخيال**.

![أيقونة "اختيار كائن".](images/choose-sprite-menu.png)

--- /task ---

--- task ---

تأكد من تحديد الكائن **Nano** في قائمة الكائن أسفل المنصة.

![قائمة الكائن، مع أطار أزرق حول الكائن Nano لإظهار أنه تم أختيار Nano.](images/nano-selected.png)


أنقر على تبويب **المقاطع البرمجية** وأضف نص للحصول على الكائن **Nano** `لقول` {:class="block3looks"}`شكراً!`:

![الكائن Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // when Nano is clicked
switch costume to [nano-b v] // Nano talking
say [Thanks!] for [2] seconds // try 1 instead of 2
switch costume to [nano-a v] // Nano smiling
```
--- /task ---

**نصيحة:** جميع الكتل البرمجية مرمزة بالألوان، لذلك ستجد مظهر التبديل ``{:class="block3looks"} الى كتلة برمجية في قائمة الكتل `الهيئة`{:class="block3looks"}.

--- task ---

**اختبار:** انقر فوق الكائن **Nano** على المنصة وتحقق من ظهور فقاعة الكلام وتغيير مظهر Nano.

--- /task ---

### Nano يستخدم لغة الإشارة

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">يستخدم الملايين من الناس لغة الإشارة للتواصل. من العلامات الشائعة لـ "شكرًا لك" **رفع يدك اليمنى إلى فمك**. 
</p>

سيستخدم Nano لغة الإشارة عن طريق تبديل المظاهر.

يمكنك تعديل المظاهر للكائنات الخاصة بك باستخدام محرر الرسام. ستقوم بتعديل مظهر Nano لجعلهم يلوحون ب "شكرًا لك".

--- task ---

انقر فوق تبويب **المظاهر** لرؤية مظاهر الكائن **Nano**:

![المظاهر المتاحة للكائن Nano.](images/nano-costumes.png)

--- /task ---

--- task ---

أنقر على مظهر **nano-b**. أنقر فوق الذراع الموجود على الجانب الأيسر، ثم أنقر فوق **مسح**.

![المظهر nano-b مع الذراع المحدد.](images/nano-arm-selected.png)

المظهر يجب أن يبدو كما يلي:

![المظهر nano-b مع الذراع المحذوف.](images/nano-arm-deleted.png)

--- /task ---

**نصيحة:** إذا قمت بخطأ ما في محرر الرسام ، يمكنك النقر فوق **تراجع**.

![أيقونة ’التراجع’.](images/nano-undo.png)

--- task ---

اذهب إلى مظهر **nano-c** وانقر على الذراع التي على الجانب الأيسر، ثم انقر على **نسخ**.

![المظهر nano-c مع الذراع المحدد.](images/nano-c-arm-selected.png)

--- /task ---

--- task ---

ارجع إلى مظهر **nano-b** وانقر على **لصق**. المظهر يجب أن يبدو كما يلي:

![المظهر nano-b مع الذراع من المظهر nano-c.](images/nano-b-new-arm.png)

--- /task ---

--- task ---

**اختبار:** انقر فوق الكائن **Nano** على المنصة وتحقق من ظهور فقاعة الكلام وتغيير مظهر Nano إلى المظهر الذي قمت بتعديله.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">لقد تعلمت كيفية التلويح بـ "شكرًا". في المرة القادمة التي تشكر فيها شخصًا ما، لماذا لا تستخدم مهارتك الجديدة؟
</p>

--- save ---
