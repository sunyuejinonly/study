# <center><font face = "仿宋" font color = "orange">Git入门教程</font></center>
## <center><font face = "仿宋">愚昧</font></center>

### 一、准备工作
1. **安装vscode**
   [安装地址]：https://git-scm.com/  

2. **安装Git**
    全部选中next即可  
3. **使用Git**
    右键桌面，点Open Git Bush
    新建一个文件夹，用于提交代码版本 
    在文件夹内右键，选择Git Bush Here
    输入git init，初始化仓库
    输入git add .，将所有文件添加到暂存区
    输入git commit -m "xx"，将文件提交到仓库(xx为备注) 
    git add 文件名 可以单独将某文件添加到仓库
4. **查看代码提交记录**
    输入git log，查看提交记录

5. **恢复代码**
    将最后一次提交的代码恢复到当前版本
    输入git checkout HEAD  文件名