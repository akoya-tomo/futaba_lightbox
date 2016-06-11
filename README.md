
## なにコレ
ブラウザ上で動くUserscriptです  

ふたば☆ちゃんねるのスレ内の画像をページ内でギャラリー風に表示します  
マウスホイールやカーソルキーでの前後移動も可能です  

Firefoxの場合、[Greasemonkey](https://addons.mozilla.org/ja/firefox/addon/greasemonkey/)を先にインスールしてからスクリプトをインストールして下さい  
Chromeの場合、[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)を先にインスールしてからスクリプトをインストールして下さい  
Opera(ver.15+)の場合、[Tampermonkey](https://addons.opera.com/extensions/details/tampermonkey-beta/)を先にインスールしてからスクリプトをインストールして下さい  

※このUserscriptは[赤福Firefox SP](http://toshiakisp.github.io/akahuku-firefox-sp/)と[ふたクロ](http://futakuro.com/)に対応しています

## インストール
[ここ](https://github.com/himuro-majika/futaba_lightbox/raw/master/futaba_lightbox.user.js)


## 使い方
* 画像のサムネイルをクリックでギャラリー表示
* ギャラリー表示中は画像の左右のナビゲーションボタンクリック、またはカーソルキー押下、または画像上でマウスホイール上下で前後移動
* ギャラリーのナビゲーションボタン以外をクリックすると新規タブで表示中の画像を開きます
* 画像の外側をクリックまたはEscキー押下するとギャラリー表示を終了します

※ギャラリー表示せず通常通り直で画像を開くときはサムネイルを中ボタンクリックするかサムネイルの上のファイル名部分をクリックしてください

※画像レス機能がない鯖(img,dat)はスレ画にしか効果がないため動作対象から除外していますが使用したい場合はスクリプトマネージャーのユーザー設定から追加してください。

## 制限事項

* 赤福の引用ポップアップから画像を開いた場合は次の画像・前の画像の順番が正しく表示されません

## ライセンス

このUserscriptには[FancyBox](http://fancyapps.com/fancybox/)を使用しています

## 更新履歴
* v1.2.3 2016-06-11
	- 赤福の続きを読むで読み込まれたレスに反応しなくなっていたのを修正
* v1.2.2 2016-06-04
	- ふたばのレイアウト変更に対応
* v1.2.0 2015-12-31
	- サイズの小さい画像を少し大きく表示するようにしました
	- パフォーマンスを改善しました  
		同時に、続きを読むで読み込んだレスに反映されるまでのラグ、及びふたクロの読み込み完了待ちのラグがなくなりました
* v1.1.0 2015-12-13
	- マウスホイールでの前後移動を追加しました
	- ギャラリーで表示している画像を含むレスに自動的にスクロールするようにしました
	- 前後のナビゲーションボタンの反応エリアを少し広くしました
	- ギャラリーの画像をクリックした際に新しいタブで画像を開くようにしました
	- ふたクロに対応しました
	- futaBoardに対応しました
	- 画像のプリロード設定を復活
	- パフォーマンスを改善しました
* v1.0.1 2015-11-02
	- 数1000レス程度のレス数の多いスレで画像の開閉が遅くなる現象を修正(黒透過背景をやめました)
	- ギャラリー表示時のページスクロールを有効に
	- 前後の画像のプリロードを停止
	- マージンを微調整
* v1.0 2015-10-14
	- 公開
