# AGI 游戏试玩集合

一个可直接对外分享的静态聚合页，用于集中展示今日 AGI 游戏原型。

## 页面内容
- 最后的人类公司
- AGI避难所

## 本地预览
该项目无依赖、无需安装：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 发布说明
仓库包含 GitHub Pages 工作流：
- 文件：`.github/workflows/deploy-pages.yml`
- 触发：推送到 `main` 或手动触发
- 发布源：GitHub Actions

## 输出文件
- `index.html`
- `README.md`
- `AGENTS.md`
- `.github/workflows/deploy-pages.yml`
