# py.Processing-animations
Animations with Processing Python Mode

## 最初に
Processingはサイトからダウンロードしてきてインストールするだけで、プログラミング環境が整います。
以下サイトからダウンロードしてください。寄付の必要はありません。「No Donation」にチェックを入れてください。
https://processing.org/download/

<img src="image-processin/py.processing-consol.png" width="600px">

まずは初期設定です。Macならメニューバーの&#34;Processing&#34;のところをクリックして環境設定を選択してください。Windowsならファイル＞設定と進みます。
以下を設定してください。
- 言語を必要な言語に（日本語）にする
- エディタとコンソールのフォントをMacなら&#34;Osaka&#34;、Windowsなら&#34;Ms Gothic&#34;にする
- 複雑なテキスト入力を有効にするにチェックを入れる
- コード補完 Ctrl-spaceにチェックを入れる

設定したら、一度再起動して下さい。

## プログラムを実行してみよう
以下のプログラムをコード入力画面にコピー＆ペーストしてください。
```python=
#プログラムを実行したとき、始めに一回だけ実行されるブロック
def setup():
  size(500,500)  #ウィンドウのサイズを設定するメソッド。500x500に設定
  background(255,255,255) #背景色を設定する関数。白に設定
  fill(0,255,0) #図形の塗りつぶし色を設定するメソッド。緑に設定

#プログラムを実行したとき、ループして実行されるブロック
def draw():
    x = 250 #円の中心のx座標を表す変数、250を代入
    y = 250 #円の中心のy座標を表す変数、250を代入
    d = 300 #円の直径を表す変数、300を代入
    ellipse(x,y,d,d); #円（楕円）を描くメソッド
```
