
--- question ---
---
legend: Question 3 sur 3
---

Dans ton projet, tu as fait faire un signe « merci » à Nano . Quel code as-tu utilisé pour que Nano porte une main à sa bouche ?

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Bonjour !] for [2] seconds 
```

  --- feedback ---

Ce code émet un son et affiche une bulle de dialogue.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50] 
think [Hum...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

Ce code change la couleur du sprite et affiche une bulle de pensée.

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
say [Merci !] for [2] seconds
switch costume to [nano-a v]
```

  --- feedback ---

Oui. Les blocs `basculer sur le costume`{:class="block3looks"} changent le costume du sprite pour que le bras bouge.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

Ce code change la couleur du sprite et joue un son.

  --- /feedback ---

--- /choices ---

--- /question ---
