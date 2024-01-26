## プロジェクトをアップグレードする

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
** Tera **スプライトを追加し、ここまでに学んだブロックのいずれかを使用して、** Tera **スプライトの「エモート」を作成します。
</div>
<div>

![ステージ上のTeraスプライト](images/tera-step.png){:width="300px"}

</div>
</div>

音声合成の拡張機能を使用したら、**Tera**に大声でしゃべらせることもできます。

[[[scratch3-text-to-speech]]]

**Tera**スプライトの個性はあなたが決められます。あなた自身の創造的なアイデアを使って楽しんでください。

```blocks3
when this sprite clicked

say [Hello!] for [2] seconds

say [Hello!]

say [] // hide speech bubble

think [Hmm...] for [2] seconds

switch costume to [tera-d v]

wait (1) seconds // 0.5 is half a second

set [color v] effect to [0] // number up to 200

clear graphic effects

play sound [pop v] until done

start sound [pop v]

speak [hello]
```

プロジェクトを「リミックス」して、好きな変更を加えることもできます。 背景やスプライトのエモート方法を変更したり、別のスプライトを選択してエモートを与えたりすることもできます。

**ヒント:** ステージの下にあるスプライトリストでスプライトをクリックして、そのスプライトのコード、コスチューム、音を変更します。

--- collapse ---
---
title: 完成したプロジェクト
---

[完成したプロジェクトはこちら](https://scratch.mit.edu/projects/606912139/){:target="_blank"}で確認できます。

--- /collapse ---

--- save ---
