# ac-excluding-unrated

「お気に入りのみ表示」にチェックを入れた際にずらっと表示される参加登録していないユーザを隠します。

ページの読み込みの際、および「お気に入りのみ表示」のチェックを入れた時（正確にはクリック時）に動きます。

This script hides users who are not registered as participants when the "Show favs only" checkbox is checked. 

URL: https://greasyfork.org/ja/scripts/472242-atcoder-standings-excluding-unrated-user

# 使い方

## 1.Tampermonkeyのインストール

まず使用ブラウザの拡張機能インストールページから _Tampermonkey_ をインストールしてください。
Chromeなら[Chrome ウェブストア](https://chrome.google.com/webstore/category/extensions?hl=ja)，Firefoxなら[Firefoxアドオン](https://addons.mozilla.org/ja/firefox/)からインストールできると思います。

## 2.Greasy Forkにアクセス

Greasy Fork(https://greasyfork.org/ja) にアクセスし当userscriptを検索する、もしくは上部のリンクにアクセスする。「スクリプトをインストール」を押すとTampermonkeyが開くので「インストール」というボタンを押して完了です。

※userscriptのインストールには十分注意してください。userscriptのインストールおよび使用による問題について作者は一切考慮しません。※

# おことわり

ページが読み込まれてから実行するためにsetTimeoutで1sec待っており、実行に時間がかかる場合があります。

改ページされるほどお気に入り登録されている場合はうまくいかないかもしれません。

他のuserscriptをインストールしている場合は競合してしまうかもしれません（少なくともac-predictorと競合しないことは手元環境で確認しました）。

そのような場合、userscriptを無効化する、もしくは「インストール済みUserScript」→「AtCoder Standings Excluding Unrated User」→コード中のdelayを少し大きくして保存してみてください。
