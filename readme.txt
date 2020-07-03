
 mkdir git_and_hub_how_to 
 cd git_and_hub_how_to
 git init .
 hub create
 少しwarning?がでる

''' 
git remote -v  # originが自動的に設定されている
  origin  git@github.com:username/repos_name.git (fetch)
  origin  git@github.com:username/repos_name.git (push)
'''
↑ではなくて

git remote add origin https://github.com/osasou/git_and_hub_how_to.git
↑ hub browseしてコピーしてきても良い 

 vim readme.md  # readmeを追加
 git add .
 git commit -m "first commit"
 git push -u origin master
 hub browse  # githubに作成されたリポジトリをブラウザで開く

完成
