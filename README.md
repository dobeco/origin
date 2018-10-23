# origin
关联远程仓库
## 第一步
1. 本地新建文件夹
2. 初始化本地仓库
```
git init
```
3. 关联仓库 用SSH关联提交不了，不知为什么，所以用HTTPS
```
git remote add origin url
```
4. 拉取代码到本地
```
git pull origin master
```
5.创建文件并提交
```
touch a.text
git add a.text
git commit -m "aa"
git push -u origin master
```
