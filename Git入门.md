# Git入门



## 视频

[Git最新教程通俗易懂-B站狂神说](https://www.bilibili.com/video/BV1FE411P7B3?p=1&vd_source=ade0ada5bbf04839a1b203ece2a01fa2)

## 精华帖

[Git的使用–如何安装和使用 github（一）](https://cloud.tencent.com/developer/article/1450659)
[Git的使用–如何将本地项目上传到Github（三种方法）（二）](https://cloud.tencent.com/developer/article/1504684)
[Git的使用–用git玩翻github（三）](https://cloud.tencent.com/developer/article/1455156)

## 文档

[Git教程-菜鸟教程](https://www.runoob.com/git/git-tutorial.html)

[Github简明教程-菜鸟教程](https://www.runoob.com/w3cnote/git-guide.html)

[Git大全-GItee](https://gitee.com/all-about-git)

## 啊嫄实践

创建仓库`study_notes`，复制这个地址备用：

![image-20221111145617933](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111145617933.png)

在本地项目`study_notes`下，右键打开`Git Bash`命令行窗口：

![image-20221111150106456](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111150106456.png)

![image-20221111150255278](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111150255278.png)

通过命令`git init`把这个文件夹变成Git可管理的仓库：

![image-20221111150440224](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111150440224.png)

会发现本地项目`study_notes`下，多了一个`.git`文件夹：



![image-20221111150555633](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111150555633.png)

可以一直使用`git status`来查看当前的状态：

![image-20221111150946096](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111150946096.png)

通过`git add .`把刚才复制过来的项目全部添加到仓库：

![image-20221111151039517](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111151039517.png)

可以一直使用`git status`来查看当前的状态：

![image-20221111151154751](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111151154751.png)

用`git commit -m "注释"`把项目提交到仓库：

![image-20221111151419951](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111151419951.png)

使用命令`git remote add origin https://github.com/csyxgithub/study_notes.git`连接远程仓库：

![image-20221111151915187](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111151915187.png)

使用命令`git push -u origin master`把本地库的所有内容推送到远程仓库：

![image-20221111152014197](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111152014197.png)

上传成功：

![image-20221111152421078](C:\Users\17484\AppData\Roaming\Typora\typora-user-images\image-20221111152421078.png)

