# Chrome開発者ツールチートシート

## 便利なショートカット

### Global keyboard shortcuts

|コマンド|説明|
|:--|:--|
|⌘+⌥+J | Consoleパネルを開く|
|⌘+⌥+I | 最後に開いていたパネルを開く|
|⌘+⇧+C | DOM要素の選択モードに入る(DevTool左上のマウスカーソルアイコンをクリックした時と同じ動作)|
|⌘+[ or ] | パネルを左 or 右へ移動|
|⌘+⇧+R | キャッシュを無視してリロード|
|⌘+⌥+F | 全検索|
|⌘+O | ファイルを開く|
|コマンド|説明|


### Mouse shortcuts by Panel
#### Elements
右クリックメニュー
|コマンド|説明|
|:--|:--|
|:active, :hover, :focus, :visitedを選択|要素に対してそれぞれの擬似要素を強制的に追加|
|Breake on... | DOM要素の操作に対してブレークポイントを張れる(ただしDOM操作にフレームワーク使ってるとあんまり嬉しくない|
|コマンド|説明|

#### Sources
|コマンド|説明|
|:--|:--|
|右上の一時停止ボタンを押す|例外発生時にbreakしてくれるようになる|

### Keyboard shortcuts by panel
#### Elements

|コマンド|説明|
|:--|:--|
|H|選択しているDOMNodeを描画領域から消す|
|⌥+DOMNode左端の矢印クリック|該当のDOM以下の全てのDOMNodeをElementPane上で展開する|

#### Styles sidebar
|コマンド|説明|
|:--|:--|
|⌘+プロパティクリック|定義元のcssへジャンプ|
|(数値のプロパティを編集中に)↑ | 値を1増やす|
|⇧+↑ | 値を10増やす|
|⇧+PageUp | 値を100増やす|  
|⌥+↑ | 値を0.1増やす|


### Source

|コマンド|説明|
|:--|:--|
|⌘+\ | resume script execution |  
|⌘+' | Step over next function call  |
|⌘+;  | Step into next function cal  |
|⌘+⇧+; | Step out of current function  |
|⌘+B | Toggle breakpoint condition    |
|行番号右クリック | Edit breakpoint condition(特定の条件の時に止めるやつとか使えます)  |
|⌥+W | Close active tab|

