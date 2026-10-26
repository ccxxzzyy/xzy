---
name: "git-push"
description: "Commits and pushes the project to GitHub remote repository. Invoke when user asks to commit, push, submit project, or deploy to GitHub/Gitee."
---

# Git Push Skill

将项目 commit 并 push 到远程仓库。

## 远程仓库地址

- **origin (Gitee)**: `https://gitee.com/xia-zhiyuan3472786880/xiazhiyuan112.git`
- **github (GitHub)**: `https://github.com/ccxxzzyy/xzy`

## 执行步骤

### 1. 查看当前状态
```bash
git status
git remote -v
```

### 2. 添加所有变更
```bash
git add -A
```

### 3. 提交
使用规范的 commit message 格式：
```bash
git commit -m "feat: 描述本次变更内容"
```

常用前缀：
- `feat:` 新功能
- `fix:` 修复 bug
- `docs:` 文档更新
- `style:` 代码格式（不影响功能）
- `refactor:` 重构
- `chore:` 构建/工具变更

### 4. 推送到远程

推送到 Gitee (origin)：
```bash
git push origin main
```

推送到 GitHub：
```bash
git push github main
```

### 5. 如果远程不存在，先添加
```bash
git remote add github https://github.com/ccxxzzyy/xzy
```

### 6. 如果远程 URL 有误，修改
```bash
git remote set-url github https://github.com/ccxxzzyy/xzy
```

## 注意事项

- 执行前先确认当前分支名（可能是 `main` 或 `master`）
- 如果 push 失败，检查 SSH key 或 token 配置
- 如果是首次推送 GitHub，确认仓库已创建
- 已设置公钥，SSH 方式可直接推送
