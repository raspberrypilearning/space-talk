
--- question ---
---
legend: Вопрос 3 из 3
---

В своем проекте ты сделал для Nano подпись «спасибо». Какой код ты использовал, чтобы Nano поднёс руку ко рту?

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Привет!] for [2] seconds 
```

  --- feedback ---

Этот код воспроизводит звук и показывает диалоговое окно.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50] 
think [Хммм...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

Этот код изменяет цвет спрайта и показывает окно мыслей.

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
say [Спасибо!] for [2] seconds
switch costume to [nano-a v]
```

  --- feedback ---

Да. Блок `изменить костюм на`{:class="block3looks"} изменяет костюм спрайта так, чтобы рука двигалась.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

Этот код меняет цвет спрайта и воспроизводит звук.

  --- /feedback ---

--- /choices ---

--- /question ---
