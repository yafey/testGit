### 零散测试工程

hello world2!  
update this code!

* 本工程主要用于测试git 的各种用法！
* 所以工程内容没什么意义！

* 这次是master分支修改该文件！

* 现在测试 分支冲突处理！首先featurel分支提交内容。

* 测试bug分支；
* 原理：将进行中的工作代码放在缓存区 git stash,然后切换至有bug的分支修复bug(一般是master分支)
* 修复完bug并提交代码后，再将工作中的代码从缓存区中提取出来；
* 所有分支共享 缓存区的内容；

* 并不是一定要把本地分支往远程推送，那么，哪些分支需要推送，哪些不需要呢？

* master分支是主分支，因此要时刻与远程同步；

* dev分支是开发分支，团队所有成员都需要在上面工作，所以也需要与远程同步；

* bug分支只用于在本地修复bug，就没必要推到远程了，除非老板要看看你每周到底修复了几个bug；

* feature分支是否推到远程，取决于你是否和你的小伙伴合作在上面开发。

