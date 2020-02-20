># git initからpushまでの方法

## ローカル➡リモート

対象のフォルダで`git init`する。
※これでローカルでgitできるぜへへへ。

ローカルと紐づけたフォルダにgitへぶち込みたいファイルorディレクトリなどを<br>
`git add`で入れていく<br>
そんで`git commit -m "hage"`<br>

git initの部分以外のadd commit はいつも通り。

ここからリモートにリポジトリを作る。
※pushするの良いけどどこに送るん？ってこと

つくったらURLコピーしてリモートのリポジトリとローカルをつなげる！
`git remote add origin リポジトリURL`

これではじめてリモートと繋がったから、ここにpushする
`git push -u origin master`

終わり！閉廷！解散！

