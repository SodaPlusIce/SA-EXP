0. 挂好梯子，防止github用不了

1. 建个文件夹，从github上拉取代码

   ```
   git clone https://github.com/SodaPlusIce/SA-EXP
   ```

2. 在本地修改文档，改，改，改

3. 准备提交自己的修改到github

   ```
   git add .    #把修改放到本地暂存区
   git commit -m "备注信息"    #本地提交commit，备注信息写点有用的信息
                              #比如“完成了3.2、3.3内容”，“修改了微服务总架构图”
   git push origin master     #把本地commit推送到远程仓库，如果前面有人push过的commit的话，你这里大概率报错
   #上述操作不报错即执行完毕，若报错，请执行以下语句
   git pull   #拉取远程的最新分支。此时大概率成功，不过也有可能出错，出错原因为你和上个人修改了同样的内容，github不知道该保留谁的修改，遇到这种情况就再说吧，暑期学校就遇到过两三次
   git push origin master  #推送到远程仓库的master分支
   ```

   

参考：

```
https://www.liaoxuefeng.com/wiki/896043488029600/900375748016320
```

