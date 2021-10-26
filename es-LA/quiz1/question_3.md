
--- question ---
---
legend: Pregunta 3 de 3
---

En tu proyecto, hiciste que Nano dijera "gracias". ¿Qué código usaste para que Nano se llevara la mano a la boca?

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Hello!] for [2] seconds 
```

  --- feedback ---

Este código reproduce un sonido y muestra una burbuja de diálogo.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50] 
think [Hmm...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

Este código cambia el color del objeto y muestra una burbuja de pensamiento.

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
say [Thanks!] for [2] seconds
switch costume to [nano-a v]
```

  --- feedback ---

Sí. El bloque `cambiar disfraz a`{:class="block3looks"} cambia el disfraz del objeto para que el brazo se mueva.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

Este código cambia el color del objeto y reproduce un sonido.

  --- /feedback ---

--- /choices ---

--- /question ---
