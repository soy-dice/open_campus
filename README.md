# open_campus

OCでの系統解析体験用コード

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soy-dice/open_campus/blob/main/oc_phylogeny_demo.ipynb)

固定の7種 + 10種類の植物から3種を選択して系統樹を推定

葉緑体ゲノムのマチュラーゼKという遺伝子のアラインメント済みのfastaをダウンロードする

実際は17種入っていて、選択した種以外の配列を除くことで対応(本当はアラインメントを作り直すべきだが...)

系統樹推定はiqtree2, 描画は基本Biopython + Matplotlib

パッケージではなく、アナログなところが多いのでややこしい