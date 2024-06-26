# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリ
  - ネット上に配置して複数人で共有するためのリポジトリ
- ローカルリポジトリ
  - 開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ


## プッシュとマージの違いは何でしょうか？
- プッシュ
  - ローカルリポジトリにコミットした変更をリモートリポジトリにアップロードすること
- マージ
  - 別のブランチの変更履歴を取り込むこと

## コミットとプッシュの違い
- コミット
  - ローカルリポジトリで編集や追加したファイルを登録し、変更履歴を残すためのもの
- プッシュ
  - ローカルリポジトリにコミットした変更をリモートリポジトリにアップロードすること


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 変更履歴を後から見たときに、どんな編集を行ったのかをすばやく認識するためのもの


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージするフロー
  - 直接リモートに更新が反映されるため、コードレビューができない
- プルリクエストでマージするフロー
  - コードレビューをしてからマージするという手順を踏むことで、事前にバグを発見する事ができる


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
1. 先にマージされた変更内容を取り込む
2. 後にマージしようとしている変更内容を取り込む
3. どちらの変更内容も取り込む