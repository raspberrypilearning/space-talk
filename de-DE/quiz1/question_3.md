
--- question ---
---
legend: Frage 3 von 3
---

In deinem Projekt hat Nano "Danke" gezeigt. Welchen Code hast du benutzt damit Nano seine Hand zu seinem Mund bewegt?

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Hallo!] for [2] seconds 
```

  --- feedback ---

Dieser Code spielt einen Klang und zeigt eine Sprechblase.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [Farbe v] effect to [50] 
think [Hmm...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

Dieser Code ändert die Farbe der Figur und zeigt eine Gedankenblase.

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
wait (0.5) seconds
switch costume to [nano-a v]
```

  --- feedback ---

Ja. Der `wechsle zu Kostüm`{:class="block3looks"} Block, ändert das Kostüm der Figur und lässt dadurch auch seinen Arm bewegen.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [Farbe v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

Der Code ändert die Farbe der Figur und spielt einen Klang ab.

  --- /feedback ---

--- /choices ---

--- /question ---
