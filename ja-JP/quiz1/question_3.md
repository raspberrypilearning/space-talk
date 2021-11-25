
--- question ---
---
legend: 質問3/3
---

プロジェクトで、Nanoに「ありがとう」の手話を行わせました。 Nanoが手を口に動かすために、どのコードを使用しましたか？

--- choices ---

- ( )
```blocks3
when this sprite clicked
start sound [Alien Creak1 v]
say [Hello!] for [2] seconds 
```

  --- feedback ---

このコードは音を鳴らし、ふきだしを表示します。

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50] 
think [Hmm...] for [2] seconds 
clear graphic effects 
```

  --- feedback ---

このコードはスプライトの色を変更し、ふきだしを表示します。

  --- /feedback ---

- (x)
```blocks3
when this sprite clicked
switch costume to [nano-b v] 
say [Thanks!] for [2] seconds
switch costume to [nano-a v]
```

  --- feedback ---

正解 `コスチュームを...にする`{:class="block3looks"}ブロックはスプリントのコスチュームを変えるため、手が動きます。

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
set [color v] effect to [50]
start sound [Alien Creak1 v] 
clear graphic effects 
```

  --- feedback ---

このコードはスプライトの色を変更し、音を鳴らします。

  --- /feedback ---

--- /choices ---

--- /question ---
