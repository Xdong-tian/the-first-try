# the-first-try

GitHub 练手仓库，用来跑通 git 基本流程：`init` → `commit` → `remote` → `push`。

- **用途**：验证账号、网络与认证链路是否正常
- **不放**：正式项目代码、模型权重、数据集、凭据
- **认证**：Git Credential Manager，首次 `push` 时浏览器授权，之后免登

## 常用命令速查

```bash
git status              # 看当前改动
git add <文件>          # 加入暂存区（先看 .gitignore）
git commit -m "说明"    # 提交到本地历史
git push                # 推送到 GitHub
git log --oneline       # 看提交历史
git remote -v           # 看远程地址
```
