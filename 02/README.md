# 远程仓库push clone

> $ git remote   

如果想查看你已经配置的远程仓库服务器，可以运行 git remote 命令。 它会列出你指定的每一个远程服务器的简写

![图1](https://github.com/wangwenquan1234/move-in-github/blob/master/img/21.png)

> $ git remote -v

指定选项 -v，会显示需要读写远程仓库使用的 Git 保存的简写与其对应的 URL。

![图1](https://github.com/wangwenquan1234/move-in-github/blob/master/img/22.png)



**运行 git remote add <shortname> <url> 添加一个新的远程 Git 仓库，同时指定一个你可以轻松引用的简写**

> $ git remote add origin https://github.com/wangwenquan1234/test.git

**origin为默认值 可以叫其他名字**

> $ git push origin master

**推到远程仓库**

> $ git clone https://github.com/wangwenquan1234/git-test

**从远端仓库克隆项目**

![图1](https://github.com/wangwenquan1234/move-in-github/blob/master/img/23.png)

![图1](https://github.com/wangwenquan1234/move-in-github/blob/master/img/24.png)

![图1](https://github.com/wangwenquan1234/move-in-github/blob/master/img/25.png)


> $ git pull https://github.com/wangwenquan1234/git-test

**同步代码**