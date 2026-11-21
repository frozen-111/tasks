# Git提交完整练习笔记
 
## 一、前期操作：进入正确文件夹

1. 打开电脑终端（Git Bash）
2. 用 cd 命令进入我的仓库文件夹
- 示例：cd 2026-Geek-Autumn 
 
 
## 二、初始化仓库（第一次操作才需要）

命令： git init 
想法：
- 执行 git init 后，这个文件夹才变成 Git仓库
- 只有变成仓库，Git 才能保存、上传到我的文件
 
## 三、设置用户名和邮箱
 
命令：git config user.name "你的用户名"
git config user.email "你的邮箱"
想法：
- Git 上传文件要知道是谁提交的
- 不设置用户名邮箱，提交会报错
- 只需要设置一次，以后永久生效
 
## 四、把文件加入暂存区
 
命令1：单个文件添加
 - git add 文件名.md 
 
命令2：所有文件一次性添加
- git add
想法：
- 我新建的文件，Git 默认是看不见的
- git add 的作用：告诉Git「我这个文件要准备提交了」
- 不加这一步，后面提交等于无效操作
 
## 五、本地正式保存
 
命令： git commit -m "本次提交说明" 
 
- 示例：git commit -m "完成hello文件和笔记提交" 

想法：
- add 只是准备，没保存
- commit 才是真正在本地电脑保存
- 每次提交必须带说明，规范操作
 
## 六、连接GitHub远程仓库
 
命令： git remote add origin 仓库地址 
想法：
- 目前文件只保存在我自己电脑，GitHub 看不到
- 这一步是绑定本地文件夹和网站上的仓库
- 了解到origin 就是远程仓库的别名，所以固定写法不用改
 
## 常见报错解决
如果提示已存在：
 git remote remove origin 
再重新绑定
想法：重复绑定会报错，先删除旧绑定，再绑新仓库地址
 
## 七、把本地文件上传到GitHub
 
命令： git push origin main 
想法：
- push = 推送、上传
- origin = 远程仓库
- 执行完这一步：电脑文件成功同步到网页GitHub
 
## 八、全程操作逻辑总结
 
完整流程顺序简述
1. 进对文件夹（cd）
2. 初始化仓库（git init）
3. 设置用户名邮箱
4. add 选中文件（放入待提交）
5. commit 本地保存
6. 绑定远程仓库
7. push 上传到 GitHub
 
简述全程逻辑：
进文件夹 → 告诉Git要哪些文件 → 本地存一下 → 连上网上仓库 → 上传完成
 
## 九、每次新增文件的通用极简流程
 
1. 新建/修改文件
2. git add .
3. git commit -m "修改内容说明"
4. git push origin main
