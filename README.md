# H5 游戏原型合集

一个集中展示近期 H5 / 微信小游戏原型的试玩入口页。

## 当前收录
- 手滑撤回王
- 摸鱼切屏王
- 已读装死大赛
- 排队别乱动：社死高峰
- 老板说反着来
- 最后的人类公司
- AGI避难所
- 福气翻翻乐
- 点点击破
- 小鱼躲管道
- 合成大西瓜 Demo

## 本地预览
无需安装依赖：

```bash
cd /Users/levy/.openclaw/workspace/projects/agi-games-hub
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 发布说明
仓库包含 GitHub Pages 工作流：
- 文件：`.github/workflows/deploy-pages.yml`
- 触发：推送到 `main` 或手动触发
- 发布源：GitHub Actions
- 线上地址：<https://levy0834.github.io/agi-games-hub/>

## 输出文件
- `index.html`
- `README.md`
- `AGENTS.md`
- `.github/workflows/deploy-pages.yml`
