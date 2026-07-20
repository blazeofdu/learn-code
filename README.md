# learn-code
learn code

# 进到你的项目目录
cd /d/your-project/

# 初始化：告诉 Git "这个目录归我管了"
git init

# 告诉 Git "你是谁"（只做一次）
git config user.name "你的名字"
git config user.email "你的邮箱"

# 把所有文件加入暂存区（准备拍照）
git add .

# 提交（拍一张快照）
git commit -m "第一次提交：初始化项目"

# 关联远程仓库（GitHub 上建的那个）
git remote add origin https://github.com/你的用户名/仓库名.git

# 推上去
git push -u origin main
