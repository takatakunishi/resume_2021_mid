# ipsj-paper-ci

情報処理学会の [LaTeXスタイルファイル](http://www.ipsj.or.jp/journal/submit/style.html) を使用（2021.6.18現在のもの）．

CI（GitHub Actions）には [tsukuba-mas/platex-action](https://github.com/tsukuba-mas/platex-action) を使用．

現状のmain.texは，研究報告用テンプレート（tech-jsample）を複製したもの．

mainブランチに「v1.0」のようなTagをつけてPushするとCIが実行され，main.pdfがReleasesに追加される．
