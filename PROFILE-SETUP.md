# 放到 GitHub 主页

1. 在 GitHub 新建一个 **Public** 仓库，仓库名必须是 `LiuliX-Xuan`，默认分支选 `main`。GitHub 会把这个同名仓库的根目录 README 显示在个人主页上。
2. 将以下内容放到仓库根目录，并保留目录结构：
   - `README.md`
   - `assets/aurora-header.gif`
   - `.github/workflows/generate-contribution-snake.yml`
   - `PROFILE-SETUP.md`（可选，仅作备忘）
3. 提交到 `main` 后，`Generate contribution snake` 工作流会自动运行；完成后主页底部的贡献动画就会显示。首次运行可能需要几分钟。

工作流使用 GitHub 自动提供的 `GITHUB_TOKEN`，不需要单独创建或填写令牌。
