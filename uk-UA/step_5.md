## Nano змінює костюм

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Зроби так, щоб Nano емоційно реагував на зміну **образів**.

Спрайти мають **образи**, щоб змінювати їхній вигляд. They are usually slightly different images of the same sprite. Щоб анімувати спрайт, можна змінювати його образ.

</div>
<div>

![Спрайт Nano говорить "Дякую!"](images/nano-step-2.png){:width="300px"}

</div>
</div>

--- task ---

Додай до проєкту спрайт **Nano** з категорії **Фантазії** category.

![Іконка 'Обрати спрайт'.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Переконайся, що спрайт **Nano** вибраний у списку Спрайтів під Сценою.

![Список спрайтів, з синьою рамкою навколо спрайта Nano, що вказує, що вибрано спрайт Nano.](images/nano-selected.png)

Click on the **Code** tab and add a script to get the **Nano** sprite to change costume using `switch costume to`{:class="block3looks"} and `wait`{:class="block3control"}. Use the drop down menu to switch between `nano-b`{:class="block3looks"} and `nano-a`{:class="block3looks"}:

![Спрайт Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // коли натиснуто на Nano
switch costume to [nano-b v] // Nano говорить
wait (0.5) seconds // спробуй 0.25 замість 0.5
switch costume to [nano-a v] // Nano посміхається
```
--- /task ---

**Порада:** Всі блоки мають кольорове позначення, тому ти знайдеш блок `змінити образ на`{:class="block3looks"} у меню блоків `Вигляд`{:class="block3looks"} та блок `чекати`{:class="block3control"} у меню блоків `Вигляд`{:class="block3control"}.

--- task ---

**Тест:** Натисни на спрайт **Nano** на Сцені та перевір, чи змінюється костюм Nano.

--- /task ---
