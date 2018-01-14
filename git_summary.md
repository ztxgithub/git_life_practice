# git 

## 创建仓库

```shell

    在本地创建新的repository(没有.git目录) push到远程的仓库中
        1.首先在github上手动创建一个新的repository
        2.在本地
            > git init
            > git add README.md
            > git commit -m "first commit"
            > git remote add origin https://github.com/ztxgithub/git_life_practice.git
            > git push -u origin master
            
    在本地已经存在的repository push 到远程的仓库中
       1.首先在github上手动创建一个新的repository
       2.在本地
            git remote add origin https://github.com/ztxgithub/git_life_practice.git
            git push -u origin master
```

