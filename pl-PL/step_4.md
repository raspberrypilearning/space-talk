## Pico odtwarza dźwięk

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Innym sposobem komunikowania się jest użycie dźwięku.
</div>
<div>

![Duszek Pico mówiący „Cześć!”](images/pico-step2.png){:width="300px"}

</div>
</div>

--- task ---

Kliknij zakładkę **Dźwięki** duszka **Pico**, a znajdziesz dźwięk **pop**. Kliknij ikonę **Odtwórz** aby go usłyszeć.

![Odtwarzanie dźwięku pop w zakładce Dźwięki.](images/pico-sound-play.png)

--- /task ---

W Scratchu jest kilka fantastycznych kosmicznych dźwięków, które możesz dodać do swojego duszka.

--- task ---

Aby wybrać nowy dźwięk, kliknij ikonę **Wybierz dźwięk** i wybierz kategorię **Kosmos** lub wpisz `space` w polu wyszukiwania.

![Ikona 'Wybierz dźwięk'.](images/sound-button.png)

![Edytor Scratcha z podświetloną opcją „Wybierz dźwięk”.](images/pico-choose-sound.png)

![Kategoria „Kosmos” w Bibliotece Dźwięków.](images/pico-space-category.png)

--- /task ---

--- task ---

Odtwórz kilka różnych dźwięków za pomocą ikon **Odtwórz**. Kiedy już znajdziesz dźwięk, którego chcesz użyć, kliknij go, aby dodać go do swojego projektu.

![Przykładowy dźwięk (Alien Creak1) pokazany poniżej dźwięku pop w zakładce Dźwięki.](images/pico-inserted-sound.png)

--- /task ---

--- task ---

Kliknij na zakładkę **Skrypt**. W menu bloków `Dźwięk`{:class="block3sound"} znajdź blok `zagraj dźwięk`{:class="block3sound"}.

Przeciągnij blok do obszaru Skrypt, pomiędzy blok `kiedy ten duszek kliknięty`{:class="block3events"}, a blok `powiedz`{:class="block3looks"}. Zrobi się luka i blok wskoczy na swoje miejsce.

![Blok "zagraj dźwięk" dodany pomiędzy dwoma blokami.](images/pico-insert-block.gif)

Twój kod powinien wyglądać tak:

![Duszek Pico.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Cześć!] for [2] seconds // ukryj dymek po 2 sekundach
```

--- /task ---

--- task ---

Upewnij się, że Twój blok `zagraj dźwięk`{:class="block3sound"} zawiera Twój wybrany dźwięk. Jeśli nie, kliknij dźwięk w bloku `zagraj dźwięk`{:class="block3sound"}, a następnie wybierz swój dźwięk z rozwijanego menu.

![Kliknięcie dźwięku Alien Creak1 w menu rozwijanym w bloku „zagraj dźwięk”.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Test:** Kliknij duszka **Pico** i sprawdź, czy dymek wyświetla się i czy słyszysz dźwięk. Jeśli nie słyszysz dźwięku, upewnij się, że dodałeś blok `zagraj dźwięk`{:class="block3sound"} pod blokiem `gdy ten duszek kliknięty`{:class="block3events"}. Sprawdź również, czy działają głośniki w komputerze lub tablecie.

--- /task ---

--- save ---

