# Terms


Repository(Repo): Thư mục dự án
Branch: Mặc định master/main
Conflict: Xung đột
# Commands

git init
git status
git add
git reset: reset lại sau khi add
git commit 'initial commit'
git log: Xem thời điểm đã lưu
git log --oneline: gọn hơn
git checkout id: trở lại commit ban đầu
git check out {branch name}
git branch
git checkout -b {branch name}
git merger {branch}
git branch -d {branch name}
git push -u origin dev: push branch local to remote

- Kéo 1 branch có sẵn trên remote nhưng chưa có ở local:
git fetch origin 
git checkout -b staging origin/staging