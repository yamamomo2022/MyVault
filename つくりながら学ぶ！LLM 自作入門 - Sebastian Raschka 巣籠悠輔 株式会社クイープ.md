---
title: つくりながら学ぶ！LLM 自作入門
subtitle: 
author: Sebastian Raschka, 巣籠悠輔, 株式会社クイープ
authors: Sebastian Raschka,巣籠悠輔,株式会社クイープ
category: Computers
categories: Computers
publisher: マイナビ出版
publishDate: 2025-03-03
totalPage: 388
coverUrl: http://books.google.com/books/content?id=Z_pJEQAAQBAJ&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api
coverSmallUrl: http://books.google.com/books/content?id=Z_pJEQAAQBAJ&printsec=frontcover&img=1&zoom=5&edge=curl&source=gbs_api
description: ※この商品はタブレットなど大きいディスプレイを備えた端末で読むことに適しています。また、文字だけを拡大することや、文字列のハイライト、検索、辞書の参照、引用などの機能が使用できません。 LLM (大規模言語モデル) をつくりながら学ぼう！ 本書はGPT型のLLM (大規模言語モデル) を一から理解して構築するために書かれました。最後まで読めばLLMの仕組みがしっかりと理解でき、独自のモデルを構築するためのスキルを身につけることができます。作成するモデルは大規模な基礎モデルと比べると規模は小さいものの概念は同じであり、最先端のLLMの構築に使われているメカニズムやテクニックを理解するための強力なツールとなるでしょう。 1章 大規模言語モデルを理解する 2章 テキストデータの準備 3章 Attentionメカニズムのコーディング 4章 テキストを生成するためのGPTモデルを一から実装する 5章 ラベルなしデータでの事前学習 6章 分類のためのファインチューニング 7章 指示に従うためのファインチューニング 付録A PyTorch 入門 付録B 参考資料 付録C 練習問題の解答 付録D 訓練ループに高度なテクニックを追加する 付録E LoRAによるパラメータ効率のよいファインチューニング Sebastian Raschka（セバスチャン・ラシュカ）： Lightning AI社でAIとLLM の研究開発に注力。以前はウィスコンシン大学マディソン校統計学部助教授。著書に『Python機械学習プログラミング［第3版］ 達人データサイエンティストによる理論と実践』（インプレス）がある。 ［監訳］巣籠 悠輔（すごもり ゆうすけ）： 株式会社MIRA代表取締役、日本ディープラーニング協会有識者会員。2018年にForbes 30 Under 30 Asia 2018 に選出。著書に『詳解ディープラーニング』、監訳書に『Pythonによるディープラーニング』(マイナビ出版) 等がある。 ［翻訳］株式会社クイープ： 1995年、米国サンフランシスコに設立。コンピュータシステムの開発、ローカライズ、コンサルティングを手がけている。2001年に日本法人を設立。主な訳書に『Python機械学習プログラミング［第3版］』『プログラマーなら知っておきたい40のアルゴリズム』（インプレス）、『なっとく！ AIアルゴリズム』（翔泳社）、『Pythonによるディープラーニング』（マイナビ出版）などがある。 http://www.quipu.co.jp ※この商品は固定レイアウト型の電子書籍です。 ※この商品はタブレットなど大きいディスプレイを備えた端末で読むことに適しています。また、文字列のハイライトや検索、辞書の参照、引用などの機能が使用できません。 ※お使いの端末で無料サンプルをお試しいただいた上でのご購入をお願いいたします。
link: https://play.google.com/store/books/details?id=Z_pJEQAAQBAJ
previewLink: http://books.google.co.jp/books?id=Z_pJEQAAQBAJ&pg=PP1&dq=%E4%BD%9C%E3%82%8A%E3%81%AA%E3%81%8C%E3%82%89%E5%AD%A6%E3%81%B6!+LLM&hl=&as_pt=BOOKS&cd=1&source=gbs_api
isbn13: PKEY:BT000181165500100101900209
---
# 3章
___
- RNNは、隠れ層に依存するので、文脈が消失する。
- アテンション機構もコサイン近似しまくってるという理解でいいのか？

# 5章
___
- 交差エントロピー誤差とは、２つの確率分布の差分を示す指標。
- 