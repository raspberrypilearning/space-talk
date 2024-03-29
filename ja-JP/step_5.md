## Nanoのコスチュームを変える

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

**コスチューム**を切り替えることで、Nanoにエモートさせます。

スプライトには、見た目を変えるための**コスチューム**があります。 コスチュームを変更してスプライトを動かすことができます。

</div>
<div>

![Nanoスプライトが「ありがとう！」と言う](images/nano-step-2.png){:width="300px"}

</div>
</div>

### Nanoが「ありがとう！ 」と合図する

--- task ---

**ファンタジー**カテゴリからプロジェクトに**Nano**スプライトを追加します。

![「スプライトを選ぶ」アイコン。](images/choose-sprite-menu.png)

--- /task ---

--- task ---

ステージの下にあるスプライトリストで**Nano**スプライトが選択されていることを確認します。

![Nanoが選択されていることを示すためにNanoスプライトの周りが青く囲まれたスプライトリスト。](images/nano-selected.png)


**コード**タブをクリックして、 **Nano**スプライトが`コスチュームを...にする`{:class="block3looks"}と`待つ`{:class="block3control"}を使用して「ありがとう」と合図するスクリプトを追加します。

![Nanoスプライト。](images/nano-sprite.png)

```blocks3
when this sprite clicked // Nanoがクリックされたとき
switch costume to [nano-b v] // Nanoが話す
say [ありがとう！] for [2] seconds // 2の代わりに1を試してみましょう
switch costume to [nano-a v] // Nanoが笑う
```
--- /task ---

**ヒント:** すべてのブロックは色で分類されているため、`コスチュームを...にする`{:class="block3looks"}ブロックは`見た目`{:class="block3looks"}ブロックメニューにあります。

--- task ---

**テスト:** ステージの**Nano**スプライトをクリックし、ふきだしが表示され、Nanoのコスチュームが変わることを確認します。

--- /task ---

### Nanoが手話で話す

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">何百万人もの人々が手話を使ってコミュニケーションをとっています。 世界で一般的に「ありがとう」を表すには、手をできるだけ平らにして指をあごにあてます。 次に手を前方に動かし、あごから離すように少し下げます。 
</p>

<!-- Add a video of someone signing -->

Nanoがコスチュームを変えることで手話を使います。

ペイントエディタを使用して、スプライトのコスチュームを編集できます。 Nanoのコスチュームを編集して、「ありがとう」の手話を行います。

--- task ---

**Nano**スプライトのコスチュームを表示するには、「**コスチューム**」タブをクリックします。

![Nanoスプライトで利用可能なコスチューム。](images/nano-costumes.png)

--- /task ---

--- task ---

**nano-b**コスチュームをクリックします。 左側の腕をクリックし、**削除**をクリックします。

![腕が選択されたnano-bコスチューム。](images/nano-arm-selected.png)

コスチュームは次のようになります。

![腕が削除されたnano-bコスチューム。](images/nano-arm-deleted.png)

--- /task ---

**ヒント:** ペイントエディタで間違えた場合は、**元に戻す**をクリックできます。

![「元に戻す」アイコン。](images/nano-undo.png)

--- task ---

**nano-c**コスチュームに移動し、左側の腕をクリックして **コピー**をクリックします。

![腕が選択されたnano-cコスチューム。](images/nano-c-arm-selected.png)

--- /task ---

--- task ---

**nano-b**コスチュームに戻り、**貼り付け**をクリックします。 コスチュームは次のようになります。

![nano-cコスチュームの腕が表示されたnano-bコスチューム。](images/nano-b-new-arm.png)

--- /task ---

--- task ---

**テスト:** **Nano**スプライトをクリックし、ふきだしが表示され、Nanoのコスチュームが編集したコスチュームに変わることを確認します。

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">これで、「ありがとう」の手話を学びました。 次に誰かに感謝するときに、ぜひ使ってみてください。
</p>

