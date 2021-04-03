# [Keyboard Quantizer](https://github.com/sekigon-gonnoc/keyboard-quantizer-doc) 用ファイル置き場

## [keyboard-quantizer-realforcemac.json](keyboard-quantizer-realforcemac.json)

[Keyboard Quantizer](https://github.com/sekigon-gonnoc/keyboard-quantizer-doc) に[Realforce for Mac](https://www.realforce.co.jp/products/R2-JPVM-WH/)をつないで使う時の[via](https://caniusevia.com/)用レイアウトファイル。Keyboard Quantizerのドキュメントにある[keyboard-quantizer.json](https://github.com/sekigon-gonnoc/keyboard-quantizer-doc/blob/master/keyboard-quantizer.json)をベースに編集したもの。なお、ライセンスは[元のファイルのライセンス(MIT)](https://github.com/sekigon-gonnoc/keyboard-quantizer-doc/blob/master/LICENSE)に従う。
なお現状ではKeyboard QuantizerがConsumer Usage Pageのキーを認識しないのでこれらキーはKC_NONEとした。

Realforce for MacはMacモードとWinモードがあり、一部のキーが送信するキーコードが変わる。また、テンキーのレイアウト、最下段のレイアウト、右上のF16～F19キーが一般的なJIS 109キーボードと異なる。モードによって挙動が変わる最下段と最上段のキーは以下の通り。

| 最上段キー            | mac    | win    | mac+FLock | win+FLock |
|:---------------|:-------|:-------|:-----------|:-----------|
| F1             | C2 70  | 3a     |        3a |        3a |
| F2             | C2 6f  | 3b     |        3b |        3b |
| F3             | 3c     | 3c     |        3c |        3c |
| F4             | 3d     | 3d     |        3d |        3d |
| F5             | 3e     | 3e     |        3e |        3e |
| F6             | 3f     | 3f     |        3f |        3f |
| F7             | C1  b6 | C1  b6 |        40 |        40 |
| F8             | C1  cd | C1  cd |        41 |        41 |
| F9             | C1  b5 | C1  b5 |        42 |        42 |
| F10            | C1  e2 | C1  e2 |        43 |        43 |
| F11            | C1  ea | C1  ea |        44 |        44 |
| F12            | C1  e9 | C1  e9 |        45 |        45 |
| F13            | 68     | 46     |           |           |
| F14            | 69     | 47     |           |           |
| F15            | 6a     | 48     |           |           |
| F16            | 6b     | 6b     |           |           |
| F17            | 6c     | 6c     |           |           |
| F18            | 6d     | 6d     |           |           |
| F19            | 6e     | 6e     |           |           |
| fn+F13         | C2 b8  | --     |           |           |
| fn+F14         | --     | --     |           |           |
| fn+F15         | --     | 49     |           |           |

| 最下段キー            | mac    | win    | mac+FLock | win+FLock |
|:---------------|:-------|:-------|:-----------|:-----------|
| lcontrol       | [e0]   | [e0]   |           |           |
| caps           | 39     | 39     |           |           |
| lcommnad       | [e2]   | [e2]   |           |           |
| loption        | [e3]   | [e3]   |           |           |
| eng            | 91     | 8b     |           |           |
|                |        |        |           |           |
| kana           | 90     | 8a     |           |           |
| rcommand       | [e7]   | 65     |           |           |
| roption        | [e6]   | [e6]   |           |           |
| rcontrol       | [e4]   | [e4]   |           |           |
| clear(numlock) | 53     | 53     |           |           |
| e/j            | 35     | 35     |           |           |

 + C1, C2 をつけた欄は Consumer Usage Pageのもの。それぞれ別のCollectionで送られてくる。C2のものはWindowsでは認識できないようだ。
 + --の欄は何もレポートを出力しないもの
 + FLockの空欄の部分はFLockなしのものと同じ
