2017-12-24
安装了git版本控制；
创建了版本库moose,email: moose_1003@163.com
学习了git int ,git add <fileName>,git commit -m "此次提交的描述" 命令

测试git status,git diff命令

学习如何回到之前版本的命令git reset --hard head^(head~100) 上一个版本用一个^,上2个版本用^^ 更多版本前head~版本数
找回之前的版本git reset --hard commit_id 用git reflog命令查看各个版本的commit_id

学习暂存区（stage），分支(master 是git默认建立的一个分支)；当git add时实际是将修改的文件放进暂存区，git commi真正的将修改提交到分支中