+++
title = "[GGW3.2.1/GGH4.X/GGH5.X] アプリケーションを利用できるユーザーを限定したい．"
date = "2010-12-16"
ttags = ["技術ノート"]
tcategories=["tech"]
banner = "img/technote.jpg"
+++

-----------------------------------------------------------------------------

*技術ノート
2010/12/16*

[番号]
技術ノート KGTN 2010121602

[現象]
[GGW3.2.1/GGH4.X/GGH5.X]
アプリケーションを利用できるユーザーを限定したい．

[説明]
以下の手順で，アプリケーションを起動出来る
（PW上にアイコンが表示される） ユーザーを限定することが出来ます．

1) アプリケーションのプロパティを開く．
2) [セキュリティ] タブをクリックする．
3) [詳細設定] ボタンをクリックする．
4) [親から継承されている...] ボックスのチェックを外す．
5) セキュリティ・ダイアログ中の [コピー] ボタンをクリックする．
6) [アクセス許可] タブの [OK] ボタンをクリックする．
7) [セキュリティ] タブの [グループ名またはユーザー名] のリストから
Users クリックする．
8) [削除] ボタンをクリックする．
9) [追加] ボタンをクリックする．
10)
ユーザーまたはグループの選択・ダイアログで，起動を許すユーザーを選択する．
11) ユーザーまたはグループの選択・ダイアログの [OK]
ボタンをクリックする．
12) [セキュリティ] タブの [OK] ボタンをクリックする．

つまり，アプリケーションに起動を許すユーザーにアクセス権
（読み取りと実行）
を与えることで，ユーザー単位に起動出来るアプリケーションを設定することが可能になります
（上記7～8で他ユーザーのアクセス権を削除しています） ．

### ファイル


[KGTN2010121602.pdf](http://techreport.kitasp.net/attachments/download/2195/KGTN2010121602.pdf) [(54.2 KB)][kitasp 技術センター, 2015/09/02
16:17]