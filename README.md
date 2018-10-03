# wcp1-8

## アイコンの導入(ここではFont Awesomeを使用)
	- CSSファイルをダウンロードしてきてlinkタグでHTMLにCSSを適用させる
	- CDN
### CDN(Content Delivery Network)
	ダウンロード不要
	通信環境が必要
	  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css">
	  上記をstyle.cssよりも上に配置
	  （下の情報がより優先されるため自分が記述したCSSは一番下へ配置）

## positionプロパティ
	要素の位置を指定する

	- static
		基準値や位置の設定を行わない

	- absolute
		絶対位置指定。ウィンドウの左上から位置を指定できる。
		親要素に relative が指定されている場合のみ、親要素の左上が基準位置となる。

	- relative
		相対位置指定。absolute が指定されている要素を子要素に持つことにより、absolute の基準位置を変更できる。

	- top / bottomプロパティ
		positionプロパティが指定されている要素にのみ指定できる。
		上から〇〇px移動させる、下から〇〇px移動させるという意味を持つ。

	- left / rightプロパティ
		positionプロパティが指定されている要素にのみ指定できる。
		左から〇〇px移動させる、右から〇〇px移動させるという意味を持つ。

