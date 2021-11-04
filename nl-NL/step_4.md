## Pico maakt een geluid

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Een andere manier om te communiceren is het gebruik van geluid.
</div>
<div>

![De Pico sprite zegt: "Hallo!"](images/pico-step2.png){:width="300px"}

</div>
</div>

--- task ---

Klik op de **Geluiden** tab voor de **Pico** sprite en je zult een **pop** geluid vinden. Klik op het **Spelen** pictogram om het **pop** geluid te horen.

![Het popgeluid afspelen op het tabblad Geluiden.](images/pico-sound-play.png)

--- /task ---

Er zijn een aantal fantastische buitenaardse geluiden in Scratch die je aan je sprite kunt toevoegen.

--- task ---

Om een nieuw geluid te kiezen, klik je op het **Kies een geluid** pictogram en selecteer de **Ruimte** categorie of typ `space` in het zoekvak.

![Het pictogram 'Kies een geluid'.](images/sound-button.png)

![De Scratch-editor met 'Kies een geluid' gemarkeerd.](images/pico-choose-sound.png)

![De categorie 'Ruimte' in de geluidsbibliotheek.](images/pico-space-category.png)

--- /task ---

--- task ---

Speel een paar verschillende geluiden met behulp van het **Play** pictogram. Zodra je een geluid hebt gevonden klik je erop om het aan jouw project toe te voegen.

![Een voorbeeldgeluid (het Alien Creak1-geluid) dat wordt weergegeven onder het popgeluid op het tabblad Geluiden.](images/pico-inserted-sound.png)

--- /task ---

--- task ---

Klik op het **Code** tabblad. Zoek bij de `Geluid`{:class="block3sound"} blokken het blok `start geluid`{:class="block3sound"}.

Sleep het blok naar het codegebied tussen `wanneer op deze sprite wordt geklikt`{:class="block3events"} blok en het `zeg`{:class="block3looks"} blok. Er ontstaat een opening en het blok klikt op zijn plaats.

![Het 'startgeluid'-blok dat tussen de twee blokken wordt toegevoegd.](images/pico-insert-block.gif)

Je code zou er als volgt uit moeten zien:

![De Pico sprite.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hallo!] for [2] seconds // spraak verbergen na 2 seconden
```

--- /task ---

--- task ---

Controleer of jouw `start geluid`{:class="block3sound"} blok het door jou gekozen geluid bevat. Als dit niet het geval is, moet je op het geluid in het `start geluid`{:class="block3sound"} blok klikken en vervolgens het door jou gekozen geluid in het keuzemenu selecteren.

![Klikken op het Alien Creak1-geluid in het keuzemenu binnen het blok 'start geluid'.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Test:** Klik op de **Pico** sprite en controleer of de tekstballon verschijnt en je het geluid kunt horen. Als je het geluid niet hoort, zorg er dan voor dat je het `start geluid`{:class="block3sound"} blok hebt toegevoegd onder het `wanneer op deze sprite wordt geklikt`{:class="block3events"} blok. Controleer ook of het geluid werkt op jouw computer of tablet.

--- /task ---

--- save ---

