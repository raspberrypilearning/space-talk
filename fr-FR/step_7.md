## Giga change de couleur

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Les sprites peuvent également utiliser des bulles de pensée et changer de couleur pour montrer leur personnalité. Tu obtiendras de Giga de faire cela.
</div>
<div>

![Le sprite Giga pensant, « Hum... ».](images/giga-step2.png){:width="300px"}

</div>
</div>

### Faire changer Giga de couleur

--- task ---

Ajoute le sprite **Giga**.

Fais glisser le sprite **Giga** sur le côté droit de la scène.

--- /task ---

--- task ---

Assure-toi que tu as sélectionné le sprite **Giga** dans la liste Sprite sous la scène. Ajoute ce code pour faire communiquer le sprite **Giga** en changeant de couleur :

![Le sprite Giga.](images/giga-sprite.png)

```blocks3
when this sprite clicked
set [color v] effect to [0] // 0 is the starting colour
think [Hmm...] for [2] seconds 
clear graphic effects // back to the starting colour
```

--- /task ---

**Astuce :** Clique sur le sprite dans la liste Sprite sous la scène avant d'ajouter ou de modifier le code, les costumes ou le son. Assure-toi d'avoir cliqué sur le bon sprite.

--- task ---

Essaie différents nombres de `1` à `200` dans le bloc `ajoute à l'effet couleur`{:class="block3looks"} jusqu'à ce que tu trouves une couleur que tu aimes.

--- /task ---

--- task ---

Modifie les mots et le nombre de secondes dans le bloc `penser`{:class="block3looks"}.

--- /task ---

--- task ---

**Tester :** Clique sur le sprite **Giga** sur la Scène et vérifie que le sprite change de couleur et affiche une bulle de pensée.

--- /task ---

