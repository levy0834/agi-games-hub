做一个静态 GitHub Pages 聚合页，项目名暂定《AGI 游戏试玩集合》。

目标：
- 做一个简洁、好看、移动端友好的单页静态站点
- 收录今天开发的两个游戏
- 每个游戏都要有：
  - 标题
  - 一句话简介
  - 类型标签
  - 元素标签
  - 试玩链接
  - GitHub 仓库链接
- 页面要像一个“小型游戏展台”，不是朴素链接列表
- 不依赖 npm install
- 直接静态 HTML/CSS/JS 即可
- 输出文件至少包括：index.html, README.md, AGENTS.md

收录游戏：
1. 最后的人类公司
- 试玩：https://levy0834.github.io/agi-human-company-demo/
- 仓库：https://github.com/levy0834/agi-human-company-demo
- 类型标签建议：策略 / 经营 / 肉鸽原型
- 元素标签建议：AGI / 公司经营 / 资源管理 / 人性抉择
- 简介建议：在 AGI 时代经营一家“最后的人类公司”，在效率与人味之间做选择。

2. AGI避难所
- 试玩：https://levy0834.github.io/agi-shelter-demo/
- 仓库：https://github.com/levy0834/agi-shelter-demo
- 类型标签建议：生存策略 / 末日经营 / 路线构筑
- 元素标签建议：AGI / 避难所 / 资源管理 / 生存抉择
- 简介建议：在算法统治后的废墟中经营地下避难所，在秩序、技术与希望之间求生。

设计要求：
- 中文页面
- 视觉风格：未来感 / 黑底 / 霓虹少量点缀 / 卡片布局
- 顶部要有页面标题与一句总介绍
- 卡片里要突出“立即试玩”按钮
- 每张卡片显示标签
- 页面底部可加一句：今日原型实验集
- 可以加轻微 hover 效果，但不要复杂动画

完成后：
1. 在当前目录生成成品
2. 补一个 GitHub Pages workflow 到 .github/workflows/deploy-pages.yml
3. 用 git 提交
4. 创建公开仓库 `agi-games-hub`（若重名可用接近名称）
5. 推送 main
6. 如果能自动完成，就把 Pages 也启用为 GitHub Actions source；若做不到，至少把仓库推上去并汇报
7. 最后输出：
   - 仓库地址
   - Pages 地址（若已有）
   - 文件列表

注意：页面要看起来像一个“可对外分享”的总入口页，不要只是文档。
