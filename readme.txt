
创建一个版本库非常简单，首先，选择一个合适的地方，创建一个空目录：

$ mkdir learngit
$ cd learngit
$ pwd
/Users/michael/learngit

1.初始化一个Git仓库，使用git init命令。
2.添加文件到Git仓库，分两步：{ 
								(1)使用命令git add <file>，注意，可反复多次使用，添加多个文件； 
								(2)使用命令git commit -m <message>，完成。
							}
3.要随时掌握工作区的状态，使用git status命令。

4.如果git status告诉你有文件被修改过，用git diff可以查看修改内容。

git log命令显示从最近到最远的提交日志，我们可以看到3次提交，最近的一次是append GPL，上一次是add distributed，最早的一次是wrote a readme file。

如果嫌输出信息太多，看得眼花缭乱的，可以试试加上--pretty=oneline参数：