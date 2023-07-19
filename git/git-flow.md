# git-flow

参考サイト

1. [【Git】git-flowを知ろう！　利用時のルールについて](https://cloudsmith.co.jp/blog/efficient/2020/08/1534208.html)

## git-flowとは
リポジトリの分岐モデル

![git-flow](https://cloudsmith.co.jp/blog/.assets/thumbnail/GitFlow-640wri.png )

各ブランチの定義

master：
プロダクトとしてのリリース用。
リリースしたらタグ付けを忘れないように

develop：
開発用ブランチ。コードが安定したらreleaseへマージする。※このブランチで作業を行わない。

feature：
機能の追加用。developから分岐して、developへマージする。

hotfix：
リリース後の緊急対応用。
masterから分岐して、masterにマージするとともにdevelopへマージする。

release：
プロダクトリリースの準備用。
リリース予定の機能やバグフィックスが反映された状態のdepelopmentから分岐する。
リリースの準備が整ったら、masterにマージするとともにdevelopにマージする。

### メリット
- 本番・開発・バクフィックスを明確化
- 並行して作業
- リリース内容を追跡可能
