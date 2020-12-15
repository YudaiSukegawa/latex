# latex
## 概要
LaTeXに関する色々。ほぼ全てのファイルはエンジンにLuaLaTeXを使用している。

無断で使用可能。
## mydocstyle.sty
### 内容
ヘッダ、フッタ、見出し、目次のデザインを提供するパッケージ。その他、一般的なパッケージの読み込み、マクロの定義を含む。
### 使用方法
目次と見出しのデザインの選択はoptionを指定するだけ。ヘッダとフッタは
~~~
\pagestyle{}
~~~
で指定。
#### 一覧
|見出しoption|目次option|ヘッダ、フッタ(pagestyle)|
|---|---|---|
|sec=normal|toc=normal(default)|normalps|
|sec=1|toc=1|ps=1|
|sec=2| |ps=2|
### その他のオプション
1. withlink
  - 見出しとヘッダ、フッタの横にページをまたぐリンクを設置。
