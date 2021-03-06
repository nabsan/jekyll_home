---
layout: post
title: Markdown Basic
category: Tips
tags: [Jekyll]
description: How to write a Jekyll site.
---

-------------
#markdown考察
-------------

##強調表現

*斜体*
**太字**
***太字かつ斜体***

##見出し表現
#大見出し
##中見出し
###小見出し

##リスト(通常）
* 弾丸リスト1行
* 弾丸リスト2行
1. 数字リスト1行
2. 数字リスト2行

##リスト(インデックス付き:ネスト表現)
* トップレベル弾丸1行目
   * サブレベル弾丸1行目
   * サブレベル弾丸2行目
   * (数字リストも同様に利用可能です)

##引用
1行目につければその次行も引用となります
複数行あっても
引用とみなされます。

引用記号はそれぞれの行頭につけても
引用とみなされます。

##リンク(aタグ)
文章の中の[サンプルリンク](http://hogehoge.com/ "Alt:別名ツールチップ文字列") です。
直接URLを表示したければ <http://hogehoge.com/>とするとよい。

##画像表示(imgタグ)
![画像リンク切れの時に表示する文字列](http://hoge.com/myimage.png "alt:別名ツールチップ文字列")

##水平線(↓は全部HRとなる。)
* * *
***
*****
- - -
-------------- 

##コードを張り付ける場合
(空行)
```python:index.py
  print 'hello py world.'
```
(空行)

また、`print 'hello py world'`という1行表記もOK。

##テーブル

|Left align | Right Align | Center align|
|:----------|------------:|:-----------:|

##TeX記法による数式
```math
TEXをここに
```

##markdown無効化
「￥」バックスラッシュで無効化できます


