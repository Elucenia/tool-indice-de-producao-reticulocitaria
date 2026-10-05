<!-- ELUCENIA technical documentation · indice-de-producao-reticulocitaria · ja · no clinical/professional/rights approval -->

# 補正網赤血球・網赤血球産生指数（RPI）

[条件・出典・許諾](https://elucenia.org/ja/tools/indice-de-producao-reticulocitaria)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 網赤血球

`ret`

% · 範囲: 0–50

### ヘマトクリット

`ht`

% · 範囲: 5–65

## 方法の版

Hillman 1969：基準Ht 45%、成熟1/1.5/2/2.5、ローカル区分40/30/20

## 記載された計算式

補正網赤血球 (%) = 網赤血球 (%) × ヘマトクリット ÷ 45.

RPI = 補正網赤血球 ÷ 成熟係数, 係数は血中成熟時間（日）: 1.0 (ヘマトクリット ≥ 40%); 1.5 (30–39%); 2.0 (20–29%); 2.5 (\< 20%).

## 限界・対象集団

網赤血球の補正は、貧血の重症度に伴う成熟時間の変化に依存します。原研究は正常な人に瀉血で生じた貧血を用い、ローカルの簡略化された範囲は抄録では確認されていません。この指数だけで、あらゆる疾患の原因や骨髄の予備能は決まりません。

## 参考文献

- [Hillman RS. Characteristics of marrow production and reticulocyte maturation in normal man in response to anemia. J Clin Invest, 1969.](https://doi.org/10.1172/JCI106001)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
