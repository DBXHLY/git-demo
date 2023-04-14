

# github教程



##1、代码白嫖

1. README.md文件是作者对于该项目的简介

2. 下载代码

   ![image-20230322101414575](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322101414575.png)

3. 将别人仓库的代码白嫖到自己仓库空间

   ![image-20230322101646561](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322101646561.png)

## 2、创建项目



1. 创建自己的仓库

   ![image-20230322101750351](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322101750351.png)

2. 上传自己的文件

   ![image-20230322101827035](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322101827035.png)

3. 傻瓜式拖拉

   ![image-20230322101909163](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322101909163.png)

4. github支持在线修改

   - 点开这个文件

     ![image-20230322102029246](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322102029246.png)

   - 点击上图的编辑按钮就可以在线修改

##3、互动交流

1. 在线留言

   ![image-20230322102154671](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322102154671.png)

2. 点击提交

   ![image-20230322102238930](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322102238930.png)

3. 不想聊了，提前结束话题。

​			![ ](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322102352566.png)

## 4、流畅访问github

1. 第一种方法下载网易UU加速器

   - 检索**学术资源**（进行加速就可以访问github）

     ![image-20230322102840351](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322102840351.png)

2. 第二种方法就是下载steam++

   - 安装steam++

     ![image-20230322103047712](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322103047712.png)

   - 找到github，点击全部启用

     ![image-20230322103209209](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322103209209.png)

  ## 5、管理你的github

1. 下载安装git

   - ![image-20230322103329319](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322103329319.png)

   - 安装完鼠标右键

     ![image-20230322103418739](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322103418739.png)

   - 选择框中标注的第二个，打开控制台窗口

     ![image-20230322103602735](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322103602735.png)

2. 打开控制台，首先配置用户名和邮箱

   ![image-20230322110407547](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322110407547.png)

3. 从github上下载源码

   - 使用git  clone

     ![image-20230322110613167](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322110613167.png)

   - 链接获取

     ![image-20230322111019356](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322111019356.png)

4. 如果自己的项目，用git来管理

   - 打开文件夹，打开git控制台

     ```
     输入：git init 创建一个git的文件夹管理自己的源码
     ```

     ![image-20230322111331459](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322111331459.png)

   - 完成一天的代码需要上传仓库备份

     ![image-20230322111533030](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322111533030.png)

   - 代码提交的两条命令

     ```
     第一条：git add .  //将文件夹中所有非空目录设置为准备提交的状态
     
     第二条：git commit -m "xxx"  //这是一条提交命令，“xxx”中的内容是自己这一次提交的备注
     ```

     ![image-20230322111925767](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322111925767.png)

   - 使用 git  log 查看提交的记录

     ![image-20230322112043729](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322112043729.png)

   - 如果代码或者项目有损坏，则可以恢复

     ```
     恢复命令:git checkout HEAD (main.py)  //()部分为要恢复的项目名称。
     ```

   - 如果代码未完成情况下，例如代码2完成，代码3未完成，则只需要提交代码2

     ![image-20230322112539822](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322112539822.png)

     ```
     只提交完成的代码：git add main.py  //将之前的 git add . 改为git add main.py，原理就是将.代表的当前文件改为要上传的具体的文件名	
     ```

5. git-创建、仓库别名

   ![image-20230322113702463](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322113702463.png)

   - ```
     git remote -v  //查看你创建过的别名
     ```

6. 常用的git命令

   ![image-20230322115007406](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322115007406.png)

7. vim中，退出编辑模式yy是复制，p是粘贴。
8. 查看工作区的状态

```
 git status  //查看当前工作区是否有未被追踪的文件
```

9. git 添加暂存区

   - git   add   文件名.xxx

   ![image-20230322124426494](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322124426494.png)

   - 从暂存区删除

   ![image-20230322124548265](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322124548265.png)

10. 提交本地库

    - ```
      git commit -m "xxx" hello.txt //提交代码
      ```

11. 查看版本信息的命令

    - ```
      git reflog   //查看引用日志信息
      git log      //查看详细信息的命令
      ```

12. 文件修改

    - 修改之后的文件还是再一次追踪

    ![image-20230322125729805](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322125729805.png)

    - ![image-20230322125842200](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322125842200.png)

13. 版本穿梭

    - 例如第三个版本不好，回到第二个版本

      ```
      git reset --hard 版本号
      ```

      ![image-20230322131047974](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322131047974.png)

14. git分支操作（提升开发效率）

    ![image-20230322132640866](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322132640866.png)

- 分支的操作
- ![image-20230322132724479](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322132724479.png)

- 创建分支

  ![image-20230322132911936](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322132911936.png)

- 切换分支

  ![image-20230322133103632](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322133103632.png)

  - 切换之后修改

  ![image-20230322133425639](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322133425639.png)

- 合并分支

  ![image-20230322133737858](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322133737858.png)

- 分支冲突

  ![image-20230322134705255](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322134705255.png)

  - 手动合并

  ![image-20230322134738700](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322134738700.png)

  ![image-20230322135151515](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322135151515.png)

## 6、团队协作机制

1. 团队内协作

   ![image-20230322140234841](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322140234841.png)

2. 跨团队协作

   ![image-20230322140709731](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322140709731.png)

3. 创建远程库（上面**2**中有详细教程）

4. 创建远程库别名

   ![image-20230322141824905](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322141824905.png)

5. git 推送本地库到远程库

   ```
   git push git-demo master   //将本地的代码推送到远程库
   ```

    ![image-20230322203254621](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322203254621.png)

6. git拉取远程库

   ```
   git pull git-demo master   //将远程库的代码拉取到本地库
   ```

   ![image-20230322203814036](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322203814036.png)

7. Linux 清屏快捷键  ctrl+L

##7、团队协作机制模拟

1. 克隆远程仓库到本地 （团队内协作第一步，假设远程仓库是岳不群上传，现在以令狐冲身份克隆远程库进行完善补充）

   ![image-20230322204820254](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322204820254.png)

   ![image-20230322204904286](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322204904286.png)

   - 克隆会如下操作：1、拉取代码。2、初始化本地仓库。3、创建别名。

   ![image-20230322205940841](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322205940841.png)

   ![image-20230322210012872](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322210012872.png)

![image-20230322210128172](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322210128172.png)

2. 补充完善代码之后，重新上传到远程库（团队协作机制第二步，以令狐冲的身份上传完善的代码到远程库，还是要经过1、修改保存代码。2、将代码添加到暂存区。3、将代码存储到本地库。4、将本地库上传到远程库。）

   ![image-20230322211821273](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322211821273.png)

3. 上传出错

   - 缺少了一步拜师的操作，远程库的创建者岳不群没有给令狐冲授权，首先要授权才能将令狐冲修改的本地库上传到远程库。

     - 拜师步骤：1、登录岳不群的账号授权（找到授权仓库--点击设置--找到管理者--邀请成员--输入成员git账号--点击邀请）

       ![image-20230322212212806](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322212212806.png)

       ![image-20230322212335887](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322212335887.png)

       - 复制邀请函点击复制链接

       ![image-20230322212502446](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322212502446.png)

       ![image-20230322212550916](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322212550916.png)

       - 然后在令狐冲的账号下

       ![image-20230322213019052](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322213019052.png)

       ![image-20230322213157425](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322213157425.png)

       ![image-20230322213249576](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322213249576.png)

       - **这时不仅令狐冲能看见这个修改之后的库，岳不群也可以看见令狐冲修改的库**

       ![image-20230322213823040](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322213823040.png)

4. 跨团队协作（以东方的身份进行修改完善）

   ![image-20230322214253216](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322214253216.png)

   - fork之后就发现东方的账号下面有git-demo，远程库

     ![image-20230322214328205](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322214328205.png)

   - 利用东方的身份打开项目修改之后提交，只是修改了东方fork过来的库，而岳不群的远程库还是没有更新。（这时就需要发送一个让岳不群接收的请求，请求查看东方完善后的库）

     ![image-20230322215030780](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322215030780.png)

     ![image-20230322215121926](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322215121926.png)

     ![image-20230322215302541](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322215302541.png)

   - 请求发送之后，在岳不群的账号中刷新就能看见请求
   - ![image-20230322215412434](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322215412434.png)

   

   - 还可以看见东方修改的代码

   - ![image-20230322215615111](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322215615111.png)

   - 还可以和东方进行交流互动

   - ![image-20230322215846611](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322215846611.png)

   - 这时作为远程库的创建者要对修改的代码进行查看，查看之后就可以提交合并申请。

   - ![image-20230322220655211](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322220655211.png)

   - ![image-20230322220734589](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230322220734589.png)

   - **合并之后岳不群，令狐冲都可以看见东方完善后的剑法。**

   ## 8、错误

   - $ git pull DB-study master
     fatal: unable to access 'https://github.com/DBXHLY/DB-study.git/': OpenSSL SSL_read: Connection was reset, errno 10054
   
   - 解决代码：git config --global http.sslVerify "false"
   
   ![image-20230330222839050](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230330222839050.png)

![image-20230330222855505](C:\Users\kobe bryant\AppData\Roaming\Typora\typora-user-images\image-20230330222855505.png)
