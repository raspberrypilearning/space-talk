## Pico zegt hallo

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Een sprite kan code, uiterlijken en geluiden hebben om de manier waarop hij eruitziet en doet, te veranderen. 
  
Je voegt codeblokken toe om Pico emoties met woorden en geluid te tonen als op de sprite wordt geklikt.
</div>
<div>

![De Pico sprite zegt: "Hallo!"](images/pico-step2.png){:width="300px"}

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Emoties**</span> zijn een manier om de persoonlijkheid van een personage in een game te laten zien. Ze kunnen spraak, geluiden, beweging en grafische effecten gebruiken, net als in Scratch. Speel je games die emoties gebruiken?
</p>

### Gebruik het zeg-blok

--- task ---

Open het `Uiterlijken`{:class="block3looks"} blokkenmenu.

Klik op een `zeg`{:class="block3looks"} `Hallo!` `voor`{:class="block3looks"} `2` `seconden`{:class="block3looks"} blok.

![De 'zeg Hallo! voor 2 seconden' blok licht op met een gele omtrek.](images/pico-say-hello-blocks-menu.png)

De **Pico** sprite toont gedurende twee seconden een tekstballon.

![De Pico sprite met "Hallo!" in een tekstballon.](images/pico-say-hello-stage.png)

**Tip:** Codeblokken in Scratch lichten op met een gele omtreklijn wanneer ze actief zijn.

--- /task ---

--- task ---

Sleep een `zeg`{:class="block3looks"} `Hallo!` `voor`{;class="block3looks"} `2` `seconden`{:class="block3looks"} blok naar het codegebied. Klik er nogmaals op.

![Het 'zeg'-blok naar het codegebied slepen en erop klikken om het uit te voeren.](images/pico-drag-say.gif)

![Het 'zeg'-blok is naar het codegebied gesleept. Het codeblok licht op met een gele omtrek.](images/pico-drag-say.png)

--- /task ---

### Laat Pico praten wanneer erop wordt geklikt (of getikt)

--- task ---

Sleep een `wanneer op deze sprite wordt geklikt`{:class="block3events"} blok uit het `Gebeurtenissen`{:class="block3events"} blokkenmenu en verbind het met de bovenkant van je `zeg`{:class="block3looks"} blok in het codegebied. De blokken zullen in elkaar klikken.

![Een animatie van de blokken die in elkaar klikken. Als er op Pico wordt geklikt, zegt het "Hallo!" gedurende twee seconden.](images/pico-snap-together.gif)

![De Pico sprite.](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Code opmerkingen

```blocks3
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
Je ziet opmerkingen in de codevoorbeelden. Je hoeft de opmerkingen niet toe te voegen wanneer je code aan jouw project toevoegt.

Als je tijd over hebt zodra je jouw project hebt afgerond, is het een goed idee om opmerkingen aan je code toe te voegen, zodat deze later gemakkelijker te begrijpen is. Om een opmerking toe te voegen, klik je met de rechtermuisknop (of tik je op een tablet en houdt je vast) op een blok in het codegebied en kies je **Commentaar toevoegen**.

![Het pop-up menu dat verschijnt wanneer je met de rechtermuisknop op een blok klikt. 'Commentaar toevoegen' is geselecteerd.](images/add-comment.png)

### Test

--- task ---

**Test:** Klik op de **Pico** sprite in het Speelveld en controleer of de tekstballon twee seconden lang verschijnt. Het is belangrijk om je code te testen om er zeker van te zijn dat deze doet wat je verwacht.

--- /task ---

--- task ---

Je hebt je project al opgeslagen en een naam gegeven. Scratch zal nu **automatisch** voor je opslaan.

Je kunt nog steeds op Opslaan klikken als je wilt, voor de zekerheid.

--- /task ---
