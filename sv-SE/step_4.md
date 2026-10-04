## Pico spelar ett ljud

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Ett annat sätt att kommunicera är genom ljud.
</div>
<div>

![Pico-sprajten säger "Hej!"](images/pico-step2.png){:width="300px"}

</div>
</div>

### Lägg till ett ljud till Pico-sprajten

--- task ---

Klicka på **Ljud**-fliken för **Pico**-sprajten så kommer du se ett **pop**-ljud. Klicka på **Spela**-ikonen för att höra **pop**-ljudet.

![Spelar upp popljudet på Ljudfliken.](images/pico-sound-play.png)

**Debug**: Om du inte hör något, kontrollera att ljudet fungerar på din dator eller surfplatta.

--- /task ---

--- task ---

För att välja ett nytt ljud, klicka på ikonen **Välj ett ljud** och välj kategorin **Rymden** eller skriv `space` i sökrutan.

!["Välj ett ljud"-ikonen.](images/sound-button.png)

![Scratch-redigeraren med "Välj ett ljud" markerat.](images/pico-choose-sound.png)

![Kategorin "Rymden" i ljudbiblioteket.](images/pico-space-category.png)

--- /task ---

--- task ---

Spela några olika ljud med **Spela** -ikonerna. När du har hittat ett ljud som du tycker om, klicka på det för att lägga till det till ditt projekt.

![Ett exempelljud (Alien Creak1 sound) som visas under popljudet i ljudfliken.](images/pico-inserted-sound.png)

--- /task ---

### Få ljudet att spela när du klickar (eller trycker) på den

--- task ---

Klicka på **Kod**fliken. I `Ljud`{:class="block3sound"}blockmenyn, hitta blocket `startljud`{:class="block3sound"}.

Dra blocket till kodområdet och sätt det mellan `när denna sprajt klickas`{:class="block3events"}blocket och `säg`{:class="block3looks"}blocket. En mellanrum kommer öppnas och blocket kommer sättas på plats.

!["Starta ljud"-blocket läggs till mellan de två blocken.](images/pico-insert-block.gif)

Din kod ska se ut så här:

![Pico-sprajten.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Testa din kod

--- task ---

Kontrollera att ditt `starta ljud`{:class="block3sound"}block har ditt valda ljud. Om det inte gör det måste du klicka på ljudet i `starta ljud`blocket {:class="block3sound"} och välja ditt ljud i menyn.

![Klicka på Alien Creak1 ljudet i menyn inom "starta ljud"-blocket.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Test:** Klicka på **Pico**sprajten och kolla att pratbubblan dyker upp och att du kan höra ljudet. Om du inte hör ljudet, se till att du har lagt till `starta ljud`{:class="block3sound"}-blocket under `:när denna sprajt klickas på`{:class="block3events"}-blocket.

--- /task ---

