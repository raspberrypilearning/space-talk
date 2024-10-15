
--- question ---
---
legend: Pregunta 3 de 3
---

En el teu projecte, has fet que Nano signes "gràcies". Quin codi vas utilitzar per fer que Nano mogui una mà a la boca?

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Hola!] for [2] seconds 
```

  --- feedback ---

Aquest codi reprodueix un so i mostra una bafarada.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50] 
think [Hmm...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

Aquest codi canvia el color del personatge i mostra una bafarada.

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
wait (0.5) seconds
switch costume to [nano-a v]
```

  --- feedback ---

Sí. Els blocs `canvien el vestit a`{:class="block3looks"} canvien el tipus de personatge perquè el braç es mogui.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

Aquest codi canvia el color del personatge i reprodueix un so.

  --- /feedback ---

--- /choices ---

--- /question ---
