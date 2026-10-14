# Microwave Engineering Tools

高専電気電子工学科5年次「マイクロ波工学」で使用する、計算・可視化スクリプトとノートブックを共有するためのリポジトリです。

## 構成

- `notebooks/`: Google Colab、Jupyter Notebook用教材
- `scripts/`: グラフ生成や数値計算のスクリプト
- `figures/`: 等価回路図と生成した図の保存先

## ノートブック

- [`notebooks/high-frequency-component-models.ipynb`](notebooks/high-frequency-component-models.ipynb): 実在インダクタ、キャパシタ、レジスタの高周波等価回路、複素インピーダンス式、数値例、振幅・位相特性

GitHubに公開後、ノートブック画面の **Open in Colab** または `https://colab.research.google.com/github/<ユーザー名>/<リポジトリ名>/blob/main/notebooks/high-frequency-component-models.ipynb` から開けます。ノートブックは NumPy と Matplotlib だけを使い、Colab上で単独実行できます。

## 等価回路図

- `figures/real-inductor.drawio`: 実在インダクタ
- `figures/real-capacitor.drawio`: 実在キャパシタ
- `figures/real-resistor.drawio`: 実在レジスタ

同名の `.png` は授業資料への貼り付け用です。元の `.drawio` を diagrams.net / draw.io で開けば編集できます。

## 方針

- 理論式、単位、使用した定数をソースに残す
- 図はスクリプトから再生成できるようにする
- 学生の個人情報、成績、提出物、認証情報は置かない

## ライセンス

公開前に教材・ソースコードのライセンスを決定して追加します。
