## Pico yn dweud helo

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Mae modd rhoi cod, gwisgoedd a seiniau i gorlun er mwyn newid y ffordd mae'n edrych a'r hyn mae'n ei wneud. 
  
Drwy ychwanegu blociau o god, bydd Pico yn ymateb gyda geiriau a seiniau wrth glicio ar y corlun.
</div>
<div>

![Pico yn dweud "Helo!"](images/pico-step2.png){:width="300px"}

</div>
</div>

I ddefnyddio blociau, galli di glicio arnyn nhw yn y ddewislen Blociau.

--- task ---

Agora'r ddewislen blociau `Edrychiad`{:class="block3looks"}.

Clicia ar y bloc `dweud`{:class="block3looks"} `Helo!` `am`{:class="block3looks"} `2` `eiliad`{:class="block3looks"}.

![Y bloc 'dweud Helo! am 2 eiliad' yn goleuo gydag amlinell melyn.](images/pico-say-Helo-blocks-menu.png)

Bydd y corlun **Pico** yn agor swigen siarad am ddwy eiliad.

![Y corlun Pico gyda "Helo!" mewn swigen siarad.](images/pico-say-Helo-stage.png)

**Awgrym:** Mae blociau cod yn Scratch yn goleuo gydag amlinell melyn pan fyddan nhw ar waith.

--- /task ---

Galli di lusgo blociau i Ardal y Cod a'u defnyddio nhw o'r fan honno.

--- task ---

Llusgau'r bloc `dweud`{:class="block3looks"} `Helo!` `am`{:class="block3looks"} `2` `eiliad`{:class="block3looks"} i Ardal y Cod. Clicia arno eto.

![Llusga'r blwch 'dweud' i Ardal y Cod a'i glicio arno i'w roi ar waith.](images/pico-drag-say.gif)

![Mae'r bloc 'dweud' wedi cael ei lusgo i Ardal y Cod. Mae'r bloc cod yn goleuo gydag amlinell melyn.](images/pico-drag-say.png)

--- /task ---

Mae modd cysylltu blociau yn Ardal y Cod i redeg mwy nag un ar y tro. Bydd y blociau cysylltiedig yn rhedeg yn eu trefn o'r brig i'r gwaelod.

--- task ---

Llusga'r bloc `pan gaiff y corlun yma ei glicio`{:class="block3events"} o'r ddewislen blociau `Digwyddiadau`{:class="block3events"} a'i gysylltu i frig dy floc `dweud`{:class="block3looks"} yn Ardal y Cod. Bydd y blociau'n snapio ynghyd.

![Animeiddiad o'r blociau'n snapio ynghyd. Wrth glicio ar Pico, bydd yn dweud "Helo!" am ddwy eiliad.](images/pico-snap-together.gif)

![Corlun Pico.](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Helo!] for [2] seconds // cuddio'r llais ar ôl 2 eiliad
```

--- /task ---

Mae Sylw yn esbonio beth mae dy god yn ei wneud.

```blocks3
say [Helo!] for [2] seconds // cuddio'r llais ar ôl 2 eiliad
```
Bydd sylwadau'n ymddangos yn enghreifftiau o'r cod. Does dim rhaid i ti ychwanegu'r sylwadau pan fyddi di'n ychwanegu cod at dy brosiect.

Os bydd gen ti rywfaint o amser ar ôl gorffen y prosiect, mae'n syniad da i ychwanegu sylwadau at dy god fel ei fod yn haws i'w ddeall yn nes ymlaen. I ychwanegu sylw, de-glicia (neu daro a dal ar dabled) ar floc yn Ardal y Cod a dewis **Ychwanegu Sylw**.

![Y ddewislen naid sy'n ymddangos pan fyddi di'n de-glicio ar floc. Wedi dewis 'Ychwanegu Sylw'.](images/add-comment.png)

--- task ---

**Prawf:** Clicia ar y corlun **Pico** ar y Llwyfan a gwneud yn siŵr bod y swigen siarad yn ymddangos am ddwy eiliad. Mae'n bwysig profi dy god i wneud yn siŵr ei fod yn gwneud beth ti'n ei ddisgwyl.

--- /task ---

--- save ---
