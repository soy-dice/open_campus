# open_campus

OCでの系統解析体験用コード

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soy-dice/open_campus/blob/main/oc_phylogeny_demo.ipynb)

基本的に上から順に実行していけばok

固定の7種 + 10種類の植物から3種を選択して系統樹を推定

| 固定7種 | 選択10種 |
| :--- | :--- |
| アボカド | サツマイモ |
| ジャガイモ | ニンジン |
| ピーマン | トマト |
| レタス | ヒマワリ |
| キャベツ | タバコ |
| ナス | メロン |
| ダイコン | ダイズ |
| | シソ |
| | オクラ |
| | ゴボウ |

葉緑体ゲノムのマチュラーゼKという遺伝子のアラインメント済みのfastaをダウンロードする<br>
なので実際は遺伝子系統樹 (種の系統樹と大きく崩れてはいないはずだが...)

実際は17種入っていて、選択した種以外の配列を除くことで対応

系統樹推定はiqtree2, 描画は基本Biopython + Matplotlib

パッケージではなく、アナログなところが多いのでややこしい