# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
* リポジトリとはファイルやディレクトリの内容を変更して記録し保存するための場所で、リモートはネット上のリポジトリのことで、ローカルはPC上にあるリポジトリのこと。


## プッシュとマージの違いは何でしょうか？
* プッシュはローカルリポジトリで変更した内容をリモートリポジトリに反映させることで、マージはブランチ同士を統合すること。


## コミットとプッシュの違い
* コミットは変更した内容をコメントとして記録すること。プッシュは変更した内容をそのままリモートに反映させること。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
* １目見てなぜ、何を、どのように変更したのかがわかる文にすること。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
* ローカルでは作業ブランチをローカル内でマージしてプッシュしているが、プルリクエストはプッシュした後に、リモートでレビュー依頼をして、レビュー指導者を介してリモートでマージされる。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
* コンフリクトが起こっているファイルを開いて、コンフリクト部分を直接直す。
<<<<<<< HEADから======= まで：今自分がcheckoutしているブランチでの変更
=======から>>>>>>> news まで：取り込もうとしたブランチでの変更
修正する時には上記の記号も消して修正する。
修正したら、コミットし直して、マージをする。