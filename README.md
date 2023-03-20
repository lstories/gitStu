## 一、Git 是什么？
git 是分布式版本控制系统

### 工作原理/流程
![image](https://user-images.githubusercontent.com/91355013/226280508-59a61209-e7f6-4a10-832b-f1e0d9eb578b.png)

### 分为四个区域：
1. Workspace：工作区
2. Index / Stage：暂存区
3. Repository：仓库区（或本地仓库）
4. Remote：远程仓库

### 安装完Git后，设置信息
- 绑定用户名, 命令:
```
git config --global user.name "xxxx"
```
- 绑定邮箱, 命令:
```
git config --global user.email "xxxxxx"
```

## 创建版本库
- 命令行输入: mkdir repoName
```
mkdir testgit
```
- 输入pwd,显示当前目录
```
pwd
```
- 将这个目录变成git的仓库, 生成了一个文件目录, 命令: git init 
```
git init
```
![image](https://user-images.githubusercontent.com/91355013/226300965-6bd947b8-6e1a-4b29-80cd-5fdb3b840e85.png)




