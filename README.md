# testupdate
测试文件库
实现文件推送至GitHub仓库
测试内容成功
命令行代码：
1、进入项目文件夹，通过命令git init将项目初始化成git本地仓库
     git init    
2、将项目内所有文件都添加到暂存区
     git add .
3、对本次的提交进行备注，以便后期版本回退等操作
    git commit -m ''           
4、在github上新建一个仓库，复制仓库地址，然后使用命令将本地仓库与远程仓库建立连接
   git remote add origin  xxx       //xxx是git仓库的地址
5、将暂存区的文件推送至远程仓库（使用强制推送'-f'）
   git push origin master -f

