## Giga byter färg

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Sprajts kan även använda tankebubblor och ändra färger för att visa sin personlighet. Du kommer få Giga att göra detta.
</div>
<div>

![Gigasprajten tänker, "Hmm...".](images/giga-step2.png){:width="300px"}

</div>
</div>

### Få Giga att ändra färg

> [!TASK]
>
> Lägg till **Giga**sprajten.
>
> Dra **Giga**sprajten till höger sida av scenen.

> [!TASK]
>
> Se till att du har **Giga**sprajten vald i sprajtlistan under scenen. Lägg till den här koden för att få **Giga**sprajten att kommunicera genom att byta färg:
>
> ![Gigasprajten.](images/giga-sprite.png)
>
> ```blocks3
> when this sprite clicked
> set [color v] effect to [0] // 0 är startfärgen
> think [Hmm...] for [2] seconds
> clear graphic effects // tillbaka till startfärgen
> ```

**Tips:** Klicka på sprajten i sprajtlistan under scenen innan du lägger till eller ändrar kod, klädsel eller ljud. Se till att du har klickat på rätt sprajt.

> [!TASK]
>
> Prova olika tal från `1` till `200` i `ändra färgeffekten till`{:class="block3looks"}blocket tills du hittar en färg som du gillar.

> [!TASK]
>
> Ändra orden och antalet sekunder i blocket `tänk`{:class="block3looks"}.

> [!TASK]
>
> **Test:** Klicka på **Giga**sprajten på scenen och kontrollera att den ändrar färg och visar en tankebubbla.
