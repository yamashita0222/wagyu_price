# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリはサーバー側にあり複数人で作業ができる。
- 一方、ローカルリポジトリは自分が使用しているデバイスに配置しユーザ一人ひとりが利用する。


## プッシュとマージの違いは何でしょうか？
- プッシュはローカルリポジトリからリモートリポジトリに反映させること
- マージは切り分けたブランチを幹ブランチに反映させること。


## コミットとプッシュの違い
- コミットは進めた作業の進捗状況をローカルリポジトリにセーブすること
- プッシュはローカルリポジトリのブランチをリモートリポジトリのブランチに反映すること


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- ログを見返した時に一目で変更内容がわかるようなものにする。
- コミットメッセージから「どんな変更を行なったのか」がわかるようなメッセージにすること。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージする時はローカルmainを経由して行われる。
- 一方、プルリクエストでマージする場合作業ブランチからリモートブランチにPushしメンター確認後にマージする。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 3通りの方法で変更を取り込む必要がある。
- 1.先にマージされた変更内容を取り込む
- 2.後にマージしようとしている変更内容を取り込む
- 3.どちらの変更内容も取り込む

