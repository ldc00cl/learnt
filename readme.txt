Git is a version control system.
Git is free software.
修改了用户名和邮箱
xiugai 

0809 

15:06修改第一次

16:22修改第二次

16:26修改第三次

18:17修改第四次，实践暂存区，并在工作区内增加license文本文件。

18:46 第五次，查看差异
18:46 第六次 比较差异
18:48 第七次 比较差异2

21：46 no8 tracks changes of files//修改管理
再次修改内容编辑·
vi readme.txt,2
 22:33修改内容：
 vi readme.txt进入文件修改 
i或insere进入插入编辑模式
esc键退出编辑切换到命令模式
输入zz或：wq保存修改并退出vi
输入:w 回车只保存文件，并提示操作结果

命令模式下：
:q! 回车放弃所有修改并退出vi
:e! 回车放弃所有修改不退出vi，回到上一次最后操作保存的状态

0811 21：48 创建新分支dev
——————————————————————————————
22；22 创建新分支feature1,解决冲突
Creating a new branch is quick and simple.
22：56修改合并
——————————————————合并冲突后的修改。

0813 23：09
分支管理策略-非fast forward模式



23：31
fast forward模式，未用—no-ff参数。测试用git log观察是否有合并历史。
//忘记在DEV分支提交（这里是在master分支提交的）
=======
0813 23:35 在dev分支上修改，不用—no-ff模测试看是否有分支历史git log
重新在dev分支上提交，但是和master分支有了冲突