自学训练营第一天课程。

任务一之前预习就已经完成，用户名 fuzaifei已经发送给辅导员。

任务二 ：创建⼀个⾃⼰的代码仓库，学会使⽤分⽀（Branch）和Pull Request
a. 阅读参考资料1
b. 创建⼀个名为 helloworld 的仓库，并在仓库内创建两个分⽀ master 和 develop
c. 在develop分⽀中创建⼀个名为 develop.txt 的⽂件，提交⼀个commit
d. 从 develop 提交⼀个 Pull Request 到 master 分⽀，并将其合并（merge）
e. 在master分⽀中再创建⼀个名为 master.txt 的⽂件，提交⼀个commit
f. 从 master 提交⼀个 pull request 到 develop 分⽀，并将其合并

任务二备注：  
熟练创建仓库，第一次成功创建分支，直接在仓库主页面的branch的选项， 单机就会出现下拉菜单，填好分支名字就可以直接创建新的分支。master是默认的主分支，不用重新创建。               疑问在之前预习的时候为什么没有学会？
如果要创建一个文档，需要先选择好分支，否则就是默认的主分支（不过创建新文档的提交的时候也可以选择提交到默认分支或者是否创建新的分支）。

在F小任务提交的时候遇到了难题，没有一次就成功提交request。
如下：在选择new pull request之后打开新的页面，在master分支下没有看到我之前创建的master.TXT文档？  点击验证后，也没有明显的改变，但是文件还是在master之下，从develop提交到master合并后，文件是转移到master了。
我重新在master分支之下创建了新的文档，这一次可以pull到develop分支中了，多次创建新文档尝试。
成功完成任务二。

任务三：在⾃⼰的本地电脑，安装 Git 桌⾯可视化⼯具 SourceTree，管理远程仓库
a. 阅读参考资料2，3
b. 通过下载地址 https://www.sourcetreeapp.com/ 安装SourceTree软件
c. 在⾃⼰创建的 helloworld 仓库中找到 clone with https 的地址
d. 通过 SourceTree 将 helloworld 仓库 clone 到本地仓库
e. 在本地仓库中创建⼀个名为 local.txt 的⽂件
f. 将本地仓库新增的⽂件提交为⼀个 commit
g. 通过 sourcetree 将本地电脑的变更推送到⾃⼰账户下的 helloworld 仓库
PS:
a. 因为sourcetree⽐github官⽅版本好⽤太多，所以要求⼤家使⽤sourcetree

备注：之前在预习的时候根据下载了好几款软件，都没有弄懂，已经卸载，安装训练营提供的。（突然死机了，还好重启，文档还在，应该是提供云缓存）
需要翻墙网络不太好，sourcetree 注册安装花费了30分钟左右。
e任务没有找到在本地仓库如何创建一个新文件。   处理方法：在本地仓库的文件夹直接创建一个txt新文档就ok。
新问题：无法提交。   处理：已经解决。需要把未暂存文件，修改为暂存所有，就可以提交了。

任务四：在其他项⽬中贡献⾃⼰的代码
a. 阅读参考资料4
b. 将公⽤的作业仓库（https://github.com/selfteaching/selfteaching-pythoncamp） fork 到⾃⼰账户下
c. 向辅导员或教练确认⾃⼰的班级⽬录，如 19100101
d. 将⾃⼰账户下的作业仓库 clone 到本地电脑
e. 在班级⽬录下，创建⼀个⽤⾃⼰的 github ⽤户名命名的⽂件夹（这个⽂件夹是将来写
作业的地⽅），并在⾃⼰⽤户名的⽂件夹下创建⼀个名为 README.md 的⽂件（这个
README.md⽂件可⽤来记录分享⾃⼰的学习⼼得）
f. 在⾃⼰⽤户名的⽂件夹下创建⼀个名为 d1_exercise_helloworld.txt 的⽂件，在⽂件中
写⼊任意内容
g. 将本地仓库新增的⽂件提交为⼀个 commit
h. 通过 sourcetree 将本地电脑的变更推送到⾃⼰账户下的作业仓库
i. 回到 github⻚⾯，在⾃⼰账户下的作业仓库⻚⾯向远程公⽤作业仓库的 master 分⽀
发起Pull Request, 在提交的 Pull Request 中 @⾃⼰的教练 提醒他检查作业


备注：在班级目录104下创建文件夹失败，只有创建的地方，疑问：文件夹=新分支吗？不是的，需要在本地创建一个文件夹。
提交失败  教练告诉我删除本地克隆，然后从新克隆，提交文档
完成作业
