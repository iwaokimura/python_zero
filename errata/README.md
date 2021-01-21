# 『ゼロから学ぶPythonプログラミング』第1刷 正誤表

<!-- 
pandocでHTMLを作成した後、tableのwidth指定を削除しなければならない。
-->

注意深く執筆したつもりですが、現時点で以下のミスや修正点が見つかっております。ご迷惑をおかけして申し訳ありません。

他に誤りや修正すべき点を見つけた方は、[GitHubのIssue](https://github.com/kaityo256/python_zero/issues)にてご指摘いただければ幸いです。

最終更新日：2021年1月25日

| ページ番号 | 誤 | 正 |
| ---  | --- | --- |
| p. 10 | 「2. 五芒星の描画」のコードの2行目 <br>`draw = ImageDraw.raw(im)` | <br> `draw = ImageDraw.raw(img)`|
| p. 34 | 図3.2の「関数が作る」のが「ローカルグループ」「中から外を見ることはできない」「右側の矢印が右向き」<BR> ![図3.2誤](fig/fig03_2_error.jpg)|「関数が作る」のは「ローカル**スコープ**」「中から外を見ることは**できる**」「右側の矢印は**左向き**」<BR>![図3.2正](fig/fig03_2_correct.jpg)|
| p. 66 | 12行目 <br>「8ビットが0でない」 | <br>「8ビット**目**が0でない」 |
| p. 124| 図8.3のクラスのコードのインデントが不正。 <br> ![図8.3誤](fig/fig08_3_error.jpg)| 正しいインデントは以下の通り。<br> ![図8.3正](fig/fig08_3_correct.jpg)|
| p. 124| 図8.4のメッセージが「`c = Counter()`」 <br> ![図8.4誤](fig/fig08_4_error.jpg)| 正しくは`c.count()` <br> ![図8.4正しい](fig/fig08_4_correct.jpg)|
| p. 156| 8行目 「一方、プログラミング言語を逐次的に解釈して実行するのがスクリプト言語であり」|「一方、プログラミング言語を逐次的に解釈して実行するのが**インタプリタ言語**であり」| 
| p. 161| 図10.7のBINARY_MULTIPLYの箱のラベルが誤っている<br> ![図10.7誤](fig/fig10_7_error.jpg) | 正しくは以下の通り。<br> ![図10.7正](fig/fig10_7_correct.jpg) |
| p. 174| 図11.6のAとCの間のコストが2 ![図11.6誤](fig/fig11_6_error.jpg) |AとCの間のコストは7 ![図11.6正](fig/fig11_6_correct.jpg)  |
| p. 174| 図11.7のAとCの間のコストが2 ![図11.7誤](fig/fig11_7_error.jpg) |AとCの間のコストは7 ![図11.6正](fig/fig11_7_correct.jpg)  |
| p. 188| 「random.randint」から2行目<br>「これは6面サイコロを10回ふることを」| <br>「これは6面サイコロを**5**回ふることを」|
| p. 197 | 6行目「いま、先ほどの図で3の所属する会社と5の所属する会社を」|「**図12.6の下の図で**3の所属する会社と5の所属する会社を」 |