git config --global user.name "foge"<br>
git config --global user.email foge@icloud.com<br>
git config --global alias.st status<br>
git config --global alias.br branch<br>
git config --global alias.brm "branch -m"<br>
git config --global alias.brd "branch -d"<br>
git config --global alias.brdd "branch -D"<br>
git config --global alias.co checkout<br>
git config --global alias.cob "checkout -b"<br>
git config --global alias.adu "add -u"<br>
git config --global alias.adup "add -u -p"<br>
git config --global alias.cm commit<br>
git config --global alias.mg "merge --no-ff"<br>
git config --global alias.mgff "merge --ff"<br>
git config --global alias.cp cherry-pick<br>
git config --global alias.log1 "log -1"<br>
git config --global alias.log2 "log -2"<br>
git config --global alias.log3 "log -3"<br>
git config --global alias.logo "log --oneline"<br>
git config --global alias.logn "log --name-status --oneline"<br>
git config --global alias.firstcom "commit --allow-empty -m \"Initial commit\""

git checkout -b new-branch origin/new-branch

git clone -b ブランチ名 https://リポジトリのアドレス

git clone -b dev git@github.com:KT0717/myDevelopTemplate.git

git merge --no-ff  xxxx -m 'merge xxxx into master'

Git コマンド早見表
https://qiita.com/kohga/items/dccf135b0af395f69144

git rebase -i --root

git push -f origin head
