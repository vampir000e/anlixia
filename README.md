
# WPS C++ 


---

## 一、学习目标

✅ 1.完成vs/Qt/cmake/git环境安装  

✅ 2.git使用  

✅ 3.C++编码规范 

⬜ 4.C++基础  

⬜ 5.设计模式  

⬜ 6.编码质量  

⬜ 7.Qt基础  

⬜ 8.计算机组成原理 & windows编程

⬜ 9.STL源码 & Qt源码

⬜ 10.KTinySTL & EverythingQt

## 二、周总结

### 01 (1.2-1.15)

#### 学习内容

1.完成软件安装

- VS_Professional_2019
- Qt_5.9.3
- cmake_3.16.0
- Git_2.31.0

2.复习了git使用 

3.C++编码规范学习

4.C++基础查缺补漏


#### 问题与解决

- **问题：git将一个项目同时push到多个仓库**  

	解决：添加远程仓库  

	git remote -v 查看远程仓库列表  

	git remote set-url --add origin XXX 添加远程仓库地址  

- **问题：VS克隆项目时提示账号密码不正确**  

	解决：系统记录了首次输入的账号密码，控制面板-用户账户-凭据管理器-windows凭证，找到对应记录，删除或更改即可  


- **问题：README.md上传至远程仓库后中文显示乱码**  

	解决：默认编码格式为GBK2312，VS-文件-高级保存选项-编码改为Unicode(UTF-8带签名), 之后再次push即可

#### 学习目标解答

##### 1.git学习目标

- **问题1： 根据下面的图片，回答问题**

![alt](https://raw.githubusercontent.com/vampir000e/my-img/main/Blog/git1.png)
	

    解释下面概念：

    - workspace
    - staging area
    - local repository
    - remote repository

- **问题2 ： 如何解决 git 冲突?**

- **问题3 : 出现下面问题的原因与解决方案是什么?**

    - 更新代码后显示： unable to unlink old ‘xxx/xxx/xx’ : invalid argument
        - 原因:
        
        - 解决方案:  

    - 更新代码后显示 :  the following untracked working tree files would be overwritten by checkout
        - 原因:
        
        - 解决方案:

    - 更新代码后显示 : your local changes to the following files would be overwritten by merge…please move or remove them before you merge
        - 原因:
        
        - 解决方案:
    
    - 版本回退git reset --hard {hash}后提示：fatal: could not parse object “hash id”
        - 原因:
        
        - 解决方案:

    - git push后提示: to https://.git![rejected] localRepo->remoteRepo(fetch first) error: failed to push some refs to ‘https://.git’Updates were rejected because the remote contain work that you do not have locally.
        - 原因:


        - 解决方案:

- **完成下列操作**
    - 克隆仓库
    - 提交修改到暂存区
    - 提交修改到远程仓库
    - 从远程仓库下载代码
    - 查看仓库状态
    - 比较文件的不同,即暂存区与工作区的差别
    - 创建分支/切换分支/查看分支列表
    - 上传代码到分支上
    - 合并分支到主分支
    - 删除分支
    - 回退到某个版本

### 02 (1.29-2.11)

### 03 (2.12-2.25)

### 04 (2.26-3.11)
