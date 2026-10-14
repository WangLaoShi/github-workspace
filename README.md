# GitHub 工作空间

这是大王用 WorkBuddy（小沃）演示 GitHub 全流程的示例仓库。

## 流程演示

- ✅ 登录 GitHub（`gh` CLI，账号 `WangLaoShi`）
- ✅ 创建公开仓库（`github-workspace`）
- ✅ 本地 `git init` + 提交 + 推送
- ✅ 从远程拉取到本地

## 命令备忘

```bash
# 建库
gh repo create github-workspace --public

# 推送
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/WangLaoShi/github-workspace.git
git push -u origin main

# 拉取
git clone https://github.com/WangLaoShi/github-workspace.git
# 或已有仓库
git pull origin main
```
