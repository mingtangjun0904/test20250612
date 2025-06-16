# test20250612
20250612:
1、在联想电脑上使用ssh和https，测试本地git推GitHub
2、echo New content
3、把test.cs改为了test.js;给test.html增加了span
20250613:
1、在公司电脑上使用https拉取了文件“test20250612”
2、合并分支dev到main
# 更新远程信息
git fetch origin

# 切换到 main 分支
git checkout main

# 拉取远程 main 最新代码
git pull origin main

# 合并远程 dev 到 main
git merge origin/dev

# 解决冲突（如有）后推送
git push origin main


git的一般使用
# 1. 修改文件后添加到暂存区
git add README.md

# 2. 提交更改（这一步你漏掉了）
git commit -m "更新 README 内容"

# 3. 推送更改到远程仓库
git push
