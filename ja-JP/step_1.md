`演算`{:class="block3operators"}ブロックの`...と...`{:class="block3operators"}ブロックを使用してテキストと変数を結合し、より長い文字列を作成できます。

`...と...`{:class="block3operators"}ブロックを使用したいブロックへドラッグします。

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

テキストを使用したいテキストに置き換えるか変数をドラッグします。

```blocks3
set [名前 v] to [Scratch]
say (join [やあ、私は猫の ] (名前)) for [2] seconds
```

**ヒント:** `...と...`{:class="block3operators"}ブロックはスペースを追加しないので、スペースを入力する必要があります。

`...と...`{:class="block3operators"}ブロックを別の`...と...`{:class="block3operators"}内へドラッグすると、より長いテキスト文字列を作成できます。

```blocks3
say (join [やあ、私は猫の ] (join (名前) [ です])) for [2] seconds
```

`やあ、私は猫の`の末尾と`です`の先頭にある「スペース」に注目してください（訳注: 英語では単語間にスペースが必要なのでこの説明がありますが、日本語では特に必要ありません）。
