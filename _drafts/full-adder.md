---
layout: post
title:  "プラレール全加算器プロジェクトご支援のお願い"
---

# はじめに
私たち線型算法同好会（[Twitter](https://twitter.com/lin_calc)，[Facebook](https://www.facebook.com/lin.calc)）は身近なもので計算をするというコンセプトで活動してきました．
主な活動成果として，プラレールを用いて半加算器という論理素子を作りました．

また，半加算器の解説記事には多くの反響をいただきました（[プラレールで半加算器を設計した話](https://cybozushiki.cybozu.co.jp/articles/m001205.html)）．

プラレール半加算器はオープンソースカンファレンスに過去3回ほど出展させていただいています．
プラレール半加算器は日々改良を重ねており，今年2017年の9月に[オープンソースカンファレンス2017 Tokyo/Fall](https://www.ospn.jp/osc2017-fall/)
にて展示した「半加算器 ver.3.0.0」は小型で高速に動作し，2編成の電車で並列計算を可能としました．

![半加算器 ver.3.0.0][overview]

<br>
こちらは実際に計算する様子です．分岐レールの*ポイントの方向*を0と1と見立て，
入力のポイントを設定したのち電車を走らせると，出力のポイントに計算結果が書き込まれるという仕組みです．

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">こちらはプラレール半加算器で1+1=2を並列で計算している様子です。 <a href="https://twitter.com/hashtag/osc17tk?src=hash&amp;ref_src=twsrc%5Etfw">#osc17tk</a> <a href="https://twitter.com/hashtag/PlarailLogicCircuit?src=hash&amp;ref_src=twsrc%5Etfw">#PlarailLogicCircuit</a> <a href="https://t.co/Dl63yy1aSk">pic.twitter.com/Dl63yy1aSk</a></p>&mdash; プラレール回路＠線型算法同好会 (@lin_calc) <a href="https://twitter.com/lin_calc/status/906559130759962624?ref_src=twsrc%5Etfw">2017年9月9日</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

<br>
# 全加算器
試行錯誤の末，全加算器を実現するレイアウトの設計が完了しました！こちらが設計図（スケッチ）です．

![プラレール全加算器の設計図][sketch]

全加算器は実際のCPUにおいても重要な要素のひとつであり，
プラレール論理回路としても重要な1ステップだと考えています．

ただ，今まで培った技術を用いてなるべく小さくなるよう設計しましたが，
高さは8階建となり，名前の通り半加算器の倍の規模となりました．

高層建築となったため手元のレール部品では数が足りず，ブロック橋脚が**200個**，ニュー坂レールが40本の他，たくさんのレール部品が追加で必要となりました．

<br>
# ご支援のお願い
私たちは来年2018年2月に開催される[オープンソースカンファレンス2018 Tokyo/Spring](https://www.ospn.jp/osc2018-spring/)で**プラレール全加算器を展示する**ことを目標としております．

足りないレール部品のご支援をいただけないでしょうか．

もとよりプラレールで2進数の足し算をさせるというよくわからない企画なので，
返礼としてパンフレットやWebページに支援してくださった方のお名前を掲載するくらいしかできませんが，
もしそれでも構わないからプラレール全加算器を見てみたい，という方がいらっしゃいましたら，ご支援をお願いいたします．

<br>
# ご支援の方法
[Amazonのほしいものリスト](http://amzn.asia/0WEl6XO)から部品をお送りいただけると嬉しいです．
その際には，メッセージ欄よりSNSやブログなどに掲載してもよいお名前，SNSアカウントをお知らせください．

<br>
## スケジュール
まず，年末年始に構築テストを行いたいと考えています．
この時の様子は報告いたします．
その後，本番であるオープンソースカンファレンス2018 Tokyo/Spring（2018年2月23日,24日）にて展示を行う予定です．

今後もプラレールで何かを計算する活動を行っていきたいと思っております，よろしくお願いいたします．


[sketch]: {{ "/assets/full-adder-challenge/sketch.jpg" | absolute_url }}
[overview]: {{ "/assets/full-adder-challenge/overview.jpg" | absolute_url }}
