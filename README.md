# UsageGitHub

GitHub使い方 俺用メモ。


*【初めてリポジトリを作ってコミットする場合。】*

適当なディレクトリを作って移動。  
`mkdir UsageGitHub`  
`cd UsageGitHub`

github用のフォルダとして初期化する。これをするとカレントディレクトリ内に.githubディレクトリが作られてこのなかいろいろ設定とか？入る。  
`git init`


例:test.txtファイルを変更したとする。

インデックス？に変更したファイルを追加する。  
ディレクトリ全体を追加したい場合は 『git add .』  
`git add test.txt`

ローカルリポジトリにコミット。 -m　でエディタを開かずにコメントを入力できる。コメントは""の中。  
`git commit -m "コメント"`

リポジトリのURLを登録。変数『origin』にURLを代入しているようなもの。  
`git remote add origin https://github.com/nsocorp/UsageGitHub`

ローカルにコミットされたものをリモートにアップロードする。『origin』はリポジトリ名。『master』はブランチ名。  
`git push origin master`



*【既存のリポジトリに初めて変更を加えてコミットする場合。】*

既存リポジトリをローカルにコピーして移動。  
`git clone https://github.com/nsocorp/UsageGitHub`  
`cd UsageGitHub`

例:test.txtファイルを変更したとする。

インデックス？に変更したファイルを追加する。  
ディレクトリ全体を追加したい場合は 『git add .』  
`git add test.txt`

ローカルリポジトリにコミット。 -m　でエディタを開かずにコメントを入力できる。コメントは""の中。  
`git commit -m "コメント"`

リポジトリのURLを登録。変数『origin』にURLを代入しているようなもの。  
`git remote add origin https://github.com/nsocorp/UsageGitHub`

ローカルにコミットされたものをリモートにアップロードする。『origin』はリポジトリ名。『master』はブランチ名。  
`git push origin master`




*【既存のリポジトリの最新情報を取得して、変更を加えてコミットする場合。】*

既存リポジトリから最新情報を取得。  
なんか本当はpullを使わずにfetchとmargeを使ったほうがいいらしい？よくわからん。  
pull = fetch + marge　のイメージっぽい。  
`git pull https://github.com/nsocorp/UsageGitHub`

例:test.txtファイルを変更したとする。

インデックス？に変更したファイルを追加する。  
ディレクトリ全体を追加したい場合は 『git add .』  
`git add test.txt`

ローカルリポジトリにコミット。 -m　でエディタを開かずにコメントを入力できる。コメントは""の中。  
`git commit -m "コメント"`

リポジトリのURLを登録。変数『origin』にURLを代入しているようなもの。  
`git remote add origin https://github.com/nsocorp/UsageGitHub`

ローカルにコミットされたものをリモートにアップロードする。『origin』はリポジトリ名。『master』はブランチ名。  
`git push origin master`
