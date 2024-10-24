
--- question ---
---
legenda: Pitanje 3 od 3
---

U svom projektu, napravili ste da Nano kaže 'hvala'.". Koji ste kod koristili kako bi napravili da Nano pomakne ruku prema ustima?

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Hello!] for [2] seconds 
```

  --- feedback ---

Ovaj kod reproducira zvuk i prikazuje govorni oblačić.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50] 
think [Hmm...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

Ovaj kod mijenja boju lika i prikazuje oblačić misli.

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
wait (0.5) seconds
switch costume to [nano-a v]
```

  --- feedback ---

Da. `Mijenja kostim u`{:class="block3looks"} blokovi mijenjaju kostim lika tako da se ruka pomiče.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

Ovaj kod mijenja boju lika i reproducira zvuk.

  --- /feedback ---

--- /choices ---

--- /question ---
