## Pico воспроизводит звук

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Другой способ общения - использование звука.
</div>
<div>

![Спрайт Pico говорит: «Привет!»](images/pico-step2.png){:width="300px"}

</div>
</div>

--- task ---

Щелкни вкладку **Звуки** для спрайта **Pico** и ты найдешь звук **pop**. Щёлкни значок **Играть**, чтобы услышать звук **pop**.

![Playing the pop sound in the Sounds tab.](images/pico-sound-play.png)

--- /task ---

В Scratch есть несколько фантастических звуков пришельцев, которые ты можешь добавить в свой спрайт.

--- task ---

Чтобы выбрать новый звук, щёлкни значок **Выбрать звук** и выбери категорию **Космос** или введи `космос` в поле поиска.

![The 'Choose a Sound' icon.](images/sound-button.png)

![The Scratch editor with 'Choose a Sound' highlighted.](images/pico-choose-sound.png)

![The 'Space' category in the Sound Library.](images/pico-space-category.png)

--- /task ---

--- task ---

Воспроизведи несколько разных звуков с помощью значков **Играть**. Как только ты найдёшь звук, который хочешь использовать, щёлкни по нему, чтобы добавить в свой проект.

![An example sound (the Alien Creak1 sound) shown below the pop sound in the Sounds tab.](images/pico-inserted-sound.png)

--- /task ---

--- task ---

Перейди на вкладку **Код**. В меню блоков `Звук`{:class="block3sound"} найди блок `включить звук`{:class="block3sound"}.

Перетащи блок в Область кода между блоком `когда спрайт нажат`{:class="block3events"} и блоком `говорить`{:class="block3looks"}. Откроется щель, и блок встанет на место.

![The 'start sound' block being added between the two blocks.](images/pico-insert-block.gif)

Твой код должен выглядеть вот так:

![The Pico sprite.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

--- task ---

Убедись, что в блоке `включить звук`{:class="block3sound"} есть выбранный тобой звук. Если это не так, тебе нужно нажать на звук в блоке `включить звук`{:class="block3sound"}, а затем выбрать выбранный звук в раскрывающемся меню.

![Clicking on the Alien Creak1 sound in the drop-down menu within the 'start sound' block.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Тест:** Нажми на спрайт **Pico** и убедись, что появляется диалоговое окно и слышен звук. Если ты не услышишь звук, убедись, что ты добавил блок `включить звук`{:class="block3sound"} под блоком `когда спрайт нажат`{:class="block3events"}. Also, check that the sound is working on your computer or tablet.

--- /task ---

--- save ---

