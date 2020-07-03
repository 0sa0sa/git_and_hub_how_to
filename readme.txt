
$ mkdir repos_name
$ cd repos_name
$ git init .
$ hub create
$ git remote -v  # originが自動的に設定されている
  origin  git@github.com:username/repos_name.git (fetch)
  origin  git@github.com:username/repos_name.git (push)
$ vim readme.md  # readmeを追加
$ git add .
$ git commit -m "first commit"
$ git push origin master
$ hub browse  # githubに作成されたリポジトリをブラウザで開く
