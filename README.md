# first-repo
This is my awesome repo.

How to use

リモートリポを作る
online page or 'git init'

ローカルリポにコピーする(clone)
 'git clone '

branchを作る
'git checkout -b'

branch一覧
'git branch'

branchの移動
'git checkout'

addする(commitするためにstaging areaに入れる)
'git add {ファイル名}'
'git add .'(全ディレクトリ)

commitする
'git commit -m {message}'

logを見る
'git log'

(master branchに反映するために)pullする
'git pull {repository} {更新先branch}'

pushする
'git push {repository} {反映させるbranch}'

pull request

------------------------
ブランチでの作業

cd c:\git/{repo name}
git config user.name 'name'
git config user.email '@gmail.com'

git checkout
git pull

working...

git add .
git commit -m 'message'

git push

-----------------------
ブランチのマージ

git checkout main
git merge sub
git push