
--- question ---
---
legend: Питання 3 з 3
---

У твоєму проєкті ти змусив Nano сказати "дякую". Який код був використаний, щоб змусити Nano піднести руку до рота?

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Hello!] for [2] seconds 
```

  --- feedback ---

Цей код відтворює звук і показує мовну бульбашку.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50] 
think [Hmm...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

Цей код змінює колір спрайта і показує бульбашку з думками.

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
wait (0.5) seconds
switch costume to [nano-a v]
```

  --- feedback ---

Так. Блоки `змінити образ на`{:class="block3looks"} змінили образ спрайта таким чином, щоб рука рухалася.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

Цей код змінює колір спрайта та відтворює звук.

  --- /feedback ---

--- /choices ---

--- /question ---
