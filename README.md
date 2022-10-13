# b3-rinkou
b3輪講で作成


## MarkDown実践

* ローカルリポジトリ

自身のローカル環境に配置するリポジトリ、普段の作業はここ

* リモートリポジトリ

サーバーに配置されてるリポジトリ、共有だったりmergeだったりpullだったりできる

![リポジトリ説明画像](https://backlog.com/ja/git-tutorial/assets/img/intro/intro2_2.png "リポジトリ")

  画像出典[https://backlog.com/ja/git-tutorial/intro/02/](https://backlog.com/ja/git-tutorial/intro/02/)

* コミット

変更差分をGitに記録する ローカルレポジトリ  
```
git log
```
でコミット履歴を確認 ハッシュ値が確認できる

``` 
git reset --hard ハッシュ値
```
で巻き戻せる

* プッシュ

ローカル上のブランチ履歴をリモートに反映

* フェッチ

リモートリポジトリの最新の履歴の取得だけ行う、作業しているブランチは異なっており、FETCH_HEADでcheckoutできる

* プル

リモートリポジトリの最新の更新内容をローカルにmergeしてくれる  
pullはfetch+merge

* ブランチ

ブランチを切って作業することで、安定版からの追加開発、共同開発などが便利

* マージ  

ブランチからブランチに変更を取り込む  
merge conflict ←:fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::fearful::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage::rage:

* クローン  

リモートリポジトリの複製

* プルリクエスト

ローカルリポジトリの変更を他の開発者に通知  
コードレビューがしやすい

* フォーク

あるレポジトリをベースとして、github上に別のレポジトリとして複製  
元のレポジトリに影響を及ぼさずにいろいろ試せる

* リポジトリの public と private の違い
 
publicは全世界に公開  
privateは自分、また招待した人のみ閲覧可能