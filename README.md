# eng2jpn_gui
ほんやくコンニャク～（ドラ〇もん声）  

英語論文をコピペしてグーグル翻訳に投げるとき，改行が入ってめんどくさいときありますよね．  
このアプリケーションでは，英文を入力する（改行が入っててもOK）と日本語訳してくれます．  

## 必要なもの
```
python3
python3-tkinter
pip3
```

## 動作確認済み環境
Cygwin  
Fedora27

## セットアップ
### Cygwin
1. install xinit python3 pip3 python3-tkinter
2. `$ pip3 install googletrans`
3. `$ run xwin -multiwindow`
4. `$ export DISPLAY=:0.0`
5. `$ ./eng2jpn_gui`

### Linux
1. install python3 pip3 python3-tkinter
2. `$ pip3 install googletrans`
3. `$ ./eng2jpn_gui`

## 使い方
1. English欄に英文を入力する．（改行が変に入っててもOK）
2. translate!ボタンをクリック．
3. Japanese欄に日本語訳が出力される．

![UI](./UI.jpg)
