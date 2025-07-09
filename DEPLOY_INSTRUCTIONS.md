# GitHub Pages 启用步骤

## 手动启用 GitHub Pages

1. 访问仓库设置页面：
   https://github.com/RJM1996/claude-code-tutorial/settings/pages

2. 在 "Source" 部分选择：
   - **"Deploy from a branch"**
   - Branch: **main**
   - Folder: **/ (root)**

3. 点击 **Save**

4. 等待几分钟后，页面会在以下地址可用：
   https://rjm1996.github.io/claude-code-tutorial/

## 如果要使用 GitHub Actions 部署（可选）

完成上述步骤后，如果想切换到 GitHub Actions 自动部署：

1. 在 Source 部分选择 **"GitHub Actions"**
2. 我们的工作流会自动触发部署

## 注意事项

- 首次部署可能需要 5-10 分钟
- 确保仓库是 Public 的
- GitHub Pages 需要仓库有内容才能启用