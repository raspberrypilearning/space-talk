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

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**エモート**</span>は、ゲーム内のキャラクターの個性を表す方法です。 Scratchで、セリフ、音、動き、グラフィック効果を使用できます。 エモートを使うゲームを遊んだことはありますか？
</p>

### 言うブロックを使用する

--- task ---

`見た目`{:class="block3looks"}ブロックメニューを開きます。

`こんにちは！``と`{:class="block3looks"}`2``秒言う`{:class="block3looks"}ブロックをクリックします。

![「こんにちは！ と 2秒間言う」ブロックの周りが黄色く光る様子。](images/pico-say-hello-blocks-menu.png)

**Pico**スプライトが2秒間ふきだしを表示します。

![Picoスプライトと「こんにちは！ 」のふきだし。](images/pico-say-hello-stage.png)

**ヒント:** Scratchのコードブロックは、実行時にまわりが黄色く光ります。

--- /task ---

--- task ---

`こんにちは！``と`{:class="block3looks"}`2``秒言う`{:class="block3looks"}ブロックをコードエリアにドラッグします。 もう一度クリックします。

![「言う」ブロックをコードエリアにドラッグし、クリックして実行する。](images/pico-drag-say.gif)

![「言う」ブロックがコードエリアにドラッグされた様子。 コードブロックの周りが黄色く光る様子。](images/pico-drag-say.png)

--- /task ---

### クリック（またはタップ）されたらPicoにしゃべらせる

--- task ---

`イベント`{:class="block3events"}ブロックメニューから`このスプライトが押されたとき`{:class="block3events"}ブロックをドラッグし、コードエリアの`言う`{:class="block3looks"}ブロックの上につなげます。 ブロック同士がくっつきます。

![ブロック同士がくっつくアニメーション。 Picoをクリックすると、「こんにちは！ 」と2秒間言う。](images/pico-snap-together.gif)

![Picoスプライト。](images/pico-sprite.png)

```blocks3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### コードコメント

```blocks3
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
コード例にはコメントが表示されています。 プロジェクトにコードを追加するときにコメントを追加する必要はありません。

プロジェクトが終了したときに時間があれば、後で理解しやすいように、コードにコメントを追加することをおすすめします。 コメントを追加するには、コードエリアでブロックを右クリック（タブレットの場合はタップして保持）し、**コメントを追加**を選択します。

![ブロックを右クリックしたときに表示されるポップアップメニュー。 「コメントを追加」が選択された状態。](images/add-comment.png)

### テスト

--- task ---

**テスト:** ステージ上の**Pico**スプライトをクリックし、ふきだしが2秒間表示されることを確認します。 コードをテストして、期待どおりに動作することを確認することが重要です。

--- /task ---

--- task ---

プロジェクトは既に保存され、名前が付けられています。 Scratchが**自動的に**保存してくれます。

念のため、必要に応じて保存をクリックすることもできます。

--- /task ---
