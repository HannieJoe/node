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

##  new URLSearchParams(); 
解决ajax 与 axios 传参格式不同,但兼容性不好