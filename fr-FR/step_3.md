## Pico dit bonjour

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Un sprite peut avoir du code, des costumes et des sons pour changer son apparence et ce qu'il fait. 
  
Ajoute des blocs de code pour que Pico s'exprime avec des mots et des sons lorsque tu cliques sur le sprite.
</div>
<div>

![Le sprite Pico disant : "Bonjour !"](images/pico-step2.png){:width="300px"}

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Les émoticônes**</span> sont un moyen de montrer la personnalité d'un personnage dans un jeu. Elles peuvent utiliser la parole, les sons, les mouvements et les effets graphiques, tout comme dans Scratch. Joues-tu à des jeux qui utilisent des émoticônes ?
</p>

### Utilise le bloc dire

--- task ---

Ouvre le menu bloc `Apparence`{:class="block3looks"}.

Clique sur un bloc `dire`{:class="block3looks"} `Bonjour !` `pendant`{:class="block3looks"} `2` `secondes`{:class="block3looks"}.

![Le "dire bonjour !" le bloc pendant 2 secondes en surbrillance avec un contour jaune.](images/pico-say-hello-blocks-menu.png)

Le sprite **Pico** affichera une bulle de dialogue pendant deux secondes.

![Le sprite Pico avec "Bonjour!" dans une bulle de dialogue.](images/pico-say-hello-stage.png)

**Astuce :** les blocs de code dans Scratch brillent d'un contour jaune lorsqu'ils sont en cours d'exécution.

--- /task ---

--- task ---

Fais glisser le bloc `dire`{:class="block3looks"} `Bonjour !` `pendant`{:class="block3looks"} `2` `secondes`{:class="block3looks"} dans la zone de Code. Clique à nouveau dessus.

![Glisser le bloc « dire » vers la zone de code et cliquer dessus pour l'exécuter.](images/pico-drag-say.gif)

![Le bloc « dire » a été déplacé vers la zone de Code. Le bloc de code en surbrillance avec un contour jaune.](images/pico-drag-say.png)

--- /task ---

### Faire parler Pico lorsqu'il est cliqué (ou tapé)

--- task ---

Fais glisser un `quand ce sprite est cliqué ` du ` bloc d'événements`{:class="block3events"} et connecte-le en haut de ton bloc `dire`{:class="block3looks" } dans la zone de Code. Les blocs vont s'imbriquer.

![Une animation des blocs qui s'imbriquent. Lorsqu'on clique sur Pico, ils disent "Bonjour !" pendant deux secondes.](images/pico-snap-together.gif)

![Le sprite Pico.](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Commentaires de code

--- task ---

```blocks3
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
Tu verras des commentaires dans les exemples de code. Tu n'as pas besoin d'ajouter les commentaires lorsque tu ajoutes du code à ton projet.

Si tu as le temps lorsque tu as terminé ton projet, c'est une bonne idée d'ajouter des commentaires à ton code afin qu'il soit plus facile à comprendre plus tard. Essaie d'ajouter un commentaire maintenant. Fais un clic droit (ou tape et maintien sur une tablette) sur un bloc dans la zone Code et choisis **Ajouter un commentaire**.

![Le menu contextuel qui apparaît lorsque tu fais un clic droit sur un bloc. « Ajouter un commentaire » est sélectionné.](images/add-comment.png)

--- /task ---

### Test

--- task ---

**Test :** Clique sur le sprite **Pico** sur la Scène et vérifie que la bulle de dialogue apparaît pendant deux secondes. Il est important de tester ton code pour t'assurer qu'il fait ce que tu attends.

--- /task ---

--- task ---

Tu as déjà sauvegardé ton projet et tu lui as donné un nom. Scratch va maintenant enregistrer ** automatiquement** pour toi.

Tu peux toujours cliquer sur Enregistrer si tu le souhaites, juste pour t'en assurer.

--- /task ---
