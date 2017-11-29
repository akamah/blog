---
layout: post
title:  "プラレール全加算器計画"
---

## あらすじ
私たち線型算法同好会 ([Twitter](https://twitter.com/lin_calc), [Facebook](https://www.facebook.com/lin.calc)) は身近なもので計算をするというコンセプトで活動してきました．
これまで主に，プラレールを用いて[半加算器を作り](https://cybozushiki.cybozu.co.jp/articles/m001205.html)．
オープンソースカンファレンスに3回ほど出展させていただいています．

例えばこちらは今年2017年の9月に[オープンソースカンファレンス2017 Tokyo/Fall](https://www.ospn.jp/osc2017-fall/)
にて展示した「半加算器 ver.3.0.0」です．

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">こちらはプラレール半加算器で1+1=2を並列で計算している様子です。 <a href="https://twitter.com/hashtag/osc17tk?src=hash&amp;ref_src=twsrc%5Etfw">#osc17tk</a> <a href="https://twitter.com/hashtag/PlarailLogicCircuit?src=hash&amp;ref_src=twsrc%5Etfw">#PlarailLogicCircuit</a> <a href="https://t.co/Dl63yy1aSk">pic.twitter.com/Dl63yy1aSk</a></p>&mdash; プラレール回路＠線型算法同好会 (@lin_calc) <a href="https://twitter.com/lin_calc/status/906559130759962624?ref_src=twsrc%5Etfw">2017年9月9日</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

## 全加算器
そしていよいよ，全加算器を実現するレイアウトの設計が完了しました．こちらが設計図（スケッチ）です．

![プラレール全加算器の設計図][sketch]

高さは8階建となり，実に半加算器の倍の規模です．

さて，肝心なレール部品なのですが，追加でニュー坂レールが40本，ブロック橋脚に至っては**180個**も必要となりました．
ありがたいことに，今までは[サイボウズ](https://cybozu.co.jp)さんと[サイボウズ・ラボ](http://labs.cybozu.co.jp)さんにスポンサーとして部品を寄付していただいたのですが，
今回からは自力で調達することになりました．

そこで，来年2月の**[オープンソースカンファレンス2018 Tokyo/Spring](https://www.ospn.jp/osc2018-spring/)でプラレール全加算器を走らせる**ことを目標とし，
レール部品をご提供いただけないでしょうか．

もとよりプラレールで2進数の足し算をさせるというよくわからない企画なので，
返礼としてパンフレットやWebページに支援してくださった方のお名前を掲載するくらいしかできませんが，
もしそれでも構わないからプラレール全加算器を見てみたい，という方がいらっしゃいましたらご支援をお願いいたします．

[Amazonのほしいものリスト](http://amzn.asia/0WEl6XO)から部品をお送りいただけると嬉しいです．


## スケジュール
まず，年末年始に構築テストを行いたいと考えています．
その後，OSC2018 Tokyo/Spring（2018年2月23日,24日）にて展示を行う予定です．


今後もプラレールで何かを計算する活動を行っていきたいと思っております，よろしくお願いいたします．

[sketch]: {{ "/assets/full-adder-challenge/sketch.jpg" | absolute_url }}
