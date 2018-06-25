```bash
echo "# node" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:HannieJoe/node.git
git push -u origin master
```

### 本地项目上传到GitHub:
1. git上创建仓库
2. 打开git bash,输入ssh-keygen -t rsa -C "email",生成公钥与私钥
3. c/administrator/.ssh 下文件 id_rsa(私钥) id_rsa.pub(公钥)
4. 进入github->settings->ssh and GPG keys 添加公钥
5. 在git bash,用ssh -T git@github.com测试是否连接成功
6. 在git bash, git init
7. 在git bash,git add .
8. 在git bash,git commit -m "msg"
9. 在git bash,git remote add origin git@github.com:HannieJoe/fourth-geneartion.git
10. 在git bash,git push -u origin master


### git基本知识
1. git add . 将所有修改提交到暂存区,有时候新增的文件可能加不进去要 git add -A
2. git commit -m '提交原因'	将暂存区的内容提交到本地版本库
3. git pull origin master(远程分支名)	将远程版本库中的内容合并到本地版本库
4. git push origin master(远程分支名) 将本地版本库中的内容提交到远程版本库


##  new URLSearchParams(); 
解决ajax 与 axios 传参格式不同,但兼容性不好