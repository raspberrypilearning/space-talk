
--- question ---
---
legend: Domanda 3 di 3
---

Nel tuo progetto, hai fatto dire a Nano "Grazie". Quale codice hai usato per portare la mano di Nano alla sua bocca?

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Ciao!] for [2] seconds 
```

  --- feedback ---

Questo codice riproduce un suono e mostra un fumetto.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50] 
think [Hmm...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

Questo codice cambia il colore dello sprite e mostra un fumetto pensieroso.

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
wait (0.5) seconds
switch costume to [nano-a v]
```

  --- feedback ---

Sì. Il blocco `passa al costume`{:class="block3looks"} cambia il costume dello sprite in modo che il braccio si muova.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

Questo codice cambia il colore dello sprite e riproduce un suono.

  --- /feedback ---

--- /choices ---

--- /question ---
