## Picoに「こんにちは」と言わせる

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
スプライトにコード、コスチューム、サウンドを設定して見た目や動きを変更できます。 
  
コードブロックを追加して、スプライトがクリックされたときにPicoが言葉と音でエモートするようにします。
</div>
<div>

![Picoスプライトが「こんにちは！」と言う](images/pico-step2.png){:width="300px"}

</div>
</div>

ブロックを使用するには、ブロックメニューでブロックをクリックします。

--- task ---

`見た目`{:class = "block3looks"} ブロックメニューを開きます。

`こんにちは!`{:class="block3looks"}と`2``秒言う`{:class="block3looks"}ブロックをクリックします。

![こんにちは！と言う 2秒間ブロックの周りが黄色く光る様子。](images/pico-say-hello-blocks-menu.png)

**Pico**スプライトが2秒間ふきだしを表示します。

![Picoスプライトと「こんにちは！」のふきだし。](images/pico-say-hello-stage.png)

**ヒント:** Scratchのコードブロックは、実行時にまわりが黄色く光ります。

--- /task ---

ブロックをコードエリアにドラッグして、そこから使用できます。

--- task ---

`こんにちは!``と`{:class="block3looks"} `2` `秒言う`{:class="block3looks"} ブロックをコードエリアにドラッグします。 もう一度クリックします。

![「言う」ブロックをコードエリアにドラッグし、クリックして実行する。](images/pico-drag-say.gif)

![「言う」ブロックがコードエリアにドラッグされた様子。 コードブロックの周りが黄色く光る様子。](images/pico-drag-say.png)

--- /task ---

コードエリアではブロックを互いに接続して、一度に複数のブロックを実行できます。 接続されたブロックは上から下に順番に実行されます。

--- task ---

`イベント`{:class="block3events"} ブロックメニューから `このスプライトが押されたとき`{:class="block3events"} ブロックをドラッグし、コードエリアの `言う`{:class="block3looks"} ブロックの上につなげます。 ブロック同士がくっつきます。

![ブロックがくっつく様子の動画。 Picoをクリックすると、「こんにちは！」と2秒間言う。](images/pico-snap-together.gif)

![Picoスプライト。](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

コメントは、コードの機能の説明です。

```blocks3
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
コード例にコメントが表示されます。 プロジェクトにコードを追加するときにコメントを追加する必要はありません。

プロジェクトが終了したときに時間があれば、あとから理解しやすいようにコードにコメントを追加することをおすすめします。 コメントを追加するには、コードエリアでブロックを右クリック (タブレットの場合はタップして保持) し、**コメントを追加**を選択します。

![ブロックを右クリックしたときに表示されるポップアップメニュー。 「コメントを追加」が選択された状態。](images/add-comment.png)

--- task ---

**テスト:** ステージ上の**Pico**スプライトをクリックし、ふきだしが2秒間表示されることを確認します。 コードをテストして、期待どおりに動作することを確認することが重要です。

--- /task ---

--- save ---