# UsageGitHub

GitHub使い方 俺用メモ。


【既存のリポジトリに初めて変更を加えてコミットする場合。】

既存リポジトリをローカルにコピー
'git clone https://github.com/nsocorp/UsageGitHub'

例:test.txtファイルを変更したとする。

インデックス？に変更したファイルを追加する。
ディレクトリ全体を追加したい場合は 『git add .』
'git add test.txt'

ローカルリポジトリにコミット。 -m　でエディタを開かずにコメントを入力できる。コメントは""の中
'git commit -m "コメント"'

リポジトリのURLを登録。変数『origin』にURLを代入しているようなもの。
'git remote add origin https://github.com/nsocorp/UsageGitHub'

ローカルにコミットされたものをリモートにアップロードする。『origin』はリポジトリ名。『master』はブランチ名
'git push origin master'
