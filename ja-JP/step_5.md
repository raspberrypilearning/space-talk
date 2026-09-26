## Nanoのコスチュームを変える

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

**コスチューム**を切り替えることで、Nanoにエモートさせます。

スプライトには、見た目を変えるための**コスチューム**があります。 They are usually slightly different images of the same sprite. コスチュームを変更してスプライトを動かすことができます。

</div>
<div>

![The Nano sprite with arms out](images/nano-b-demo.png){:width="300px"}

</div>
</div>

--- task ---

**ファンタジー**カテゴリからプロジェクトに**Nano**スプライトを追加します。

![「スプライトを選ぶ」アイコン。](images/choose-sprite-menu.png)

--- /task ---

--- task ---

ステージの下にあるスプライトリストで**Nano**スプライトが選択されていることを確認します。

![Nanoが選択されていることを示すためにNanoスプライトの周りが青く囲まれたスプライトリスト。](images/nano-selected.png)

**コード**タブをクリックして、 **Nano**スプライトが`コスチュームを...にする`{:class="block3looks"}と`待つ`{:class="block3control"}を使用して「ありがとう」と合図するスクリプトを追加します。 Use the drop down menu to switch between `nano-b`{:class="block3looks"} and `nano-a`{:class="block3looks"}:

![Nanoスプライト。](images/nano-sprite.png)

```blocks3
when this sprite clicked // Nanoがクリックされたとき
switch costume to [nano-b v] // Nanoが話す
say [ありがとう！ ] for [2] seconds // 2の代わりに1を試してみましょう
switch costume to [nano-a v] // Nanoが笑う
```
--- /task ---

**ヒント:** すべてのブロックは色で分類されているため、`コスチュームを...にする`{:class="block3looks"}ブロックは`見た目`{:class="block3looks"}ブロックメニューにあります。

--- task ---

**テスト:** ステージの**Nano**スプライトをクリックし、ふきだしが表示され、Nanoのコスチュームが変わることを確認します。

--- /task ---
