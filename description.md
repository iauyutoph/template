# #include <bits/stdc++.h>
gccでしか使えないとかなんとか。<iostream>とか<algorithm>とかまとめられるから便利だけどどうせテンプレートでコピペするならあまり意味ない気もする。

# using namespace std;
coutとかの頭にstd::(cout)をつけるのを省略できる。

# using ll = long long;
long longと書くところをllと書くだけでいいので時短になる。

# const ABC, abc, mod, INF, INFL;
定数とかをまとめている。
ABCは大文字アルファベット、abcは小文字アルファベットで文字列系の問題で使ったり。
modはmod998244353で答えるときに使う。
INFはint型の初期化とかでINFLはlong long型の初期化。マイナスにしたい場合は-INFとか書いとけばいい。

# const dx[5], dy[5];
幅優先探索とかマスを移動するときに便利。

# rep0
repマクロの0からn-1まで。
repマクロについてはAPG4bなどで調べてみてください。

# rep1
repマクロの1からnまで。
結構1から始めた方がいいことも多いので作った。
任意の位置から始められるrepマクロの書き方もあるが0と1以外から始めることが少ないのでわかりやすい方を採用。

# rrep0
repマクロのn-1から0まで。
要はrep0を逆から見ているということ。

# rrep1
rrep0と同様。nから1まで。

# el "\n"
改行はendlより"\n"のほうが高速らしいがendlを書く癖が抜けないのでこうした。

# coutY/coutN
AtCoderだとYes/No出力はそこそこ多かったので作った。ぶっちゃけあんま変わらん。

# all(x)
vectorのソートとかで地味に便利そうだと思って作った。

# get_vec(x)
入力をvectorに入れたいときに使えるかもと思って作った。

# char_itr関数
文字cがABC/abcの何文字目かを返す関数。
文字列問題でそこそこ書くので作った。
