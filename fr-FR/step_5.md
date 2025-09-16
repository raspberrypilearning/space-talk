## Nano change de costume

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Donne une émotion à Nano en changeant de **costumes**.

Les sprites ont des **costumes** pour changer leur apparence. Il s'agit généralement d'images légèrement différentes du même sprite. Pour animer un sprite, tu peux changer ses costumes.

</div>
<div>

![Le sprite Nano disant : "Merci !"](images/nano-step-2.png){:width="300px"}

</div>
</div>

--- task ---

Ajoute le **Nano** à ton projet de la catégorie **Fantaisie**.

![L'icône « Choisir un Sprite ».](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Assure-toi que le sprite **Nano** est sélectionné dans la liste Sprite sous la scène.

![La liste Sprite, avec une bordure bleue autour du sprite Nano pour montrer que Nano est sélectionné.](images/nano-selected.png)

Clique sur l'onglet **Code** et ajoute un script pour faire `dire`{:class="block3looks"} `Merci !` au sprite **Nano** : Utilise le menu déroulant pour basculer de `nano-b`{:class="block3looks"} à `nano-a`{:class="block3looks"} :

![Le sprite Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // quand on clique sur Nano
switch costume to [nano-b v] // Nano parle
wait (0.5) seconds // essayez 0.25 au lieu de 0.5
switch costume to [nano-a v] // Nano souriant
```
--- /task ---

**Astuce :** Tous les blocs sont codés par couleur, tu trouveras donc le bloc `basculer sur le costume`{:class="block3looks"} dans le menu des blocs `Apparences`{:class="block3looks"} et le bloc `attendre`{:class="block3control"} dans le menu `Contrôles`{:class="block3control"}.

--- task ---

**Test :** Clique sur le sprite **Nano** sur la Scène et vérifie que la bulle de dialogue apparaît et que le costume de Nano change.

--- /task ---
