# AGENTS.md

## 项目目标
构建一个移动端友好的单页静态站点，作为 AGI 游戏原型的对外试玩入口。

## 技术约束
- 纯静态实现（HTML/CSS）
- 不依赖 npm install
- 可直接部署到 GitHub Pages

## 内容规范
- 页面为中文
- 每个游戏需包含：标题、简介、类型标签、元素标签、试玩链接、仓库链接
- 页面视觉为未来感深色风格，突出“立即试玩”入口

## 发布流程
1. 修改 `index.html`
2. 提交到 `main`
3. GitHub Actions 自动执行 `.github/workflows/deploy-pages.yml`
4. 发布到 GitHub Pages
