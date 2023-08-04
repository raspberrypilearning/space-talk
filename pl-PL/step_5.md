## Nano zmienia kostiumy

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Sprawisz, że Nano będzie emotował poprzez zmianę **kostiumów**.

Duszki mają **kostiumy**, które pozwalają im zmienić wygląd. Aby animować duszka, możesz zmienić jego kostiumy.

</div>
<div>

![Duszek Nano mówiący „Dzięki!”](images/nano-step-2.png){:width="300px"}

</div>
</div>

### Nano mówi „Dzięki!”

--- task ---

Dodaj duszka **Nano** do swojego projektu z kategorii **Fikcja**.

![Ikona „Wybierz duszka”.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Upewnij się, że duszek **Nano** jest zaznaczony na Liście duszków pod Sceną.

![Lista duszków z niebieską obwódką wokół duszka Nano wskazującą, że Nano został wybrany.](images/nano-selected.png)


Kliknij zakładkę **Skrypt** i dodaj kod, aby duszek **Nano** powiedział {:class="block3looks"} "Dzięki!" używając `zmień kostium na`{:class="block3looks"} i`oczekiwanie`{:class="block3control"}:

![Duszek Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // when Nano is clicked
switch costume to [nano-b v] // Nano talking
wait (0.5) seconds // try 0.25 instead of 0.5
switch costume to [nano-a v] // Nano smiling
```
--- /task ---

**Wskazówka:** Wszystkie bloki są oznaczone kolorami, więc znajdziesz blok `zmień kostium na`{:class="block3looks"} w menu bloków `Wygląd`{:class="block3looks"}i blok `oczekiwania`{:class="block3control"}w menu bloków `Kontroli`{:class="block3control"}.

--- task ---

**Test:** Kliknij duszka **Nano** na Scenie i sprawdź, czy kostium Nano się zmienia.

--- /task ---

### Nano używa języka migowego

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">Miliony ludzi porozumiewają się w języku migowym. Powszechnym sposobem wyrażenia „Dziękuję” jest ułożenie palców na podbródku tak płasko, jak to możliwe. Następnie rękę przesuwa się do przodu, z dala od podbródka i lekko w dół. 
</p>

<!-- Add a video of someone signing -->

Nano posłuży się językiem migowym poprzez zmianę kostiumów.

Możesz edytować kostiumy swoich duszków za pomocą Edytora graficznego. Zmodyfikujesz kostium Nano tak, aby pokazał "dziękuję".

--- task ---

Kliknij zakładkę **Kostiumy**, aby zobaczyć kostiumy dla duszka **Nano**:

![Kostiumy dostępne dla duszka Nano.](images/nano-costumes.png)

--- /task ---

--- task ---

Kliknij kostium **nano-b**. Kliknij ramię po lewej stronie, a następnie kliknij **Usuń**.

![Kostium nano-b z wybranym ramieniem.](images/nano-arm-selected.png)

Kostium powinien wyglądać następująco:

![Kostium nano-b z usuniętym ramieniem.](images/nano-arm-deleted.png)

--- /task ---

**Wskazówka:** Jeśli popełnisz błąd w Edytorze graficznym, możesz kliknąć **Cofnij**.

![Ikona „Cofnij”.](images/nano-undo.png)

--- task ---

Przejdź do kostiumu **nano-c** i kliknij ramię po lewej stronie, a następnie kliknij **Kopiuj**.

![Kostium nano-c z wybranym ramieniem.](images/nano-c-arm-selected.png)

--- /task ---

--- task ---

Wróć do kostiumu **nano-b** i kliknij **Wklej**. Kostium powinien wyglądać następująco:

![Kostium nano-b z ramieniem z kostiumu nano-c.](images/nano-b-new-arm.png)

--- /task ---

--- task ---

**Test:** Kliknij duszka **Nano** na Scenie i sprawdź, czy wyświetla się dymek z tekstem, a kostium Nano się zmienia na kostium który wyedytowałeś.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">Nauczyłeś się pokazywać gest „dziękuję”. Gdy następnym razem będziesz komuś dziękować, może wykorzystasz swoją nową umiejętność?
</p>

