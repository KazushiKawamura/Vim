#Vim覚え書き
* [保存と終了](https://github.com/KazushiKawamura/Vim#保存と終了)
* [モード切替](https://github.com/KazushiKawamura/Vim#モード切替)
* [カーソル移動](https://github.com/KazushiKawamura/Vim#カーソル移動)
* [通常モード](https://github.com/KazushiKawamura/Vim#通常モード)
* [ウィンドウ分割](https://github.com/KazushiKawamura/Vim#ウィンドウ分割)
* [文字列検索](https://github.com/KazushiKawamura/Vim#文字列検索)

## 保存と終了

|command|operation|
|---|---|
|:q|終了|
|:q!|変更を破棄して終了|
|:w|保存|

## モード切替

|command|operation|
|---|---|
|i|現在のカーソル位置から挿入モードへ|
|A|行の末尾から挿入モードへ|
|I|行の先頭から挿入モードへ|
|o|改行してから挿入モードへ(カーソル行の下に挿入)|
|O|カーソル行を改行してから挿入モードへ(カーソル行の上に挿入)|
|Esc|通常モードへ|

## カーソル移動

|command|operation|
|---|---|
|:{数字}|{数字}行に移動|
|:0|先頭行に移動|
|:$|最終行に移動|
|^|行の先頭に移動|
|$|行の末尾に移動|
|Ctrl u|半画面分上に移動|
|Ctrl d|半画面分下に移動|

## 通常モード

|command|operation|
|---|---|
|x|カーソルの後ろを一字削除|
|yy|行コピー|
|dd|行カット|
|p|ペースト|
|{数字}yy|{数字}行コピー|
|{数字}dd|{数字}行カット|
|u|undo⇔redo|

## ウィンドウ分割

|command|operation|
|---|---|
|:vs|ウィンドウを縦方向に分割し，左側に新しいファイルを表示|
|:sp|ウィンドウを横方向に分割し，上側に新しいファイルを表示|
|Ctrl ww|カーソルを次のウィンドウに移動|
|Ctrl wr|ウィンドウを下方向，右方向に移動|

## 文字列検索
|command|operation|
|---|---|
|/{検索文字列}|下方向に{検索文字列}を検索|
|?{検索文字列}|上方向に{検索文字列}を検索|
|*|カーソル位置の単語を下方向に検索|
|#|カーソル位置の単語を上方向に検索|
|n|/や?で検索した後，順方向に次の検索結果にジャンプ|
|N|/や?で検索した後，逆方向に次の検索結果にジャンプ|
