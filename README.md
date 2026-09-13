# 青石之下 · Under the Blue Stone

Ren'Py 制作的推理文字游戏（Reasoning text game）的 Web 版本。

## Play

线上版本部署于 GitHub Pages：

**https://jt1934378847-bot.github.io/underthebluestone/**

## Tech

- Ren'Py Web（`renpy.wasm`），游戏逻辑由 Ren'Py 打包为 `.data/.wasm` 资源
- 纯静态站点：`index.html` + `renpy-pre.js` / `renpy.js` + 图片 / 音频资源
- 包含 PWA manifest 与 App Icons

## Run locally

纯静态项目，任意静态文件服务器打开 `index.html` 即可：

```bash
python3 -m http.server
# 浏览器访问 http://localhost:8000
```

## Deploy

推送到 `main` 分支会自动触发 GitHub Pages 构建。

配置位置：Settings → Pages → **Deploy from a branch** → `main` / `(root)`。

## Note

> 本 README 由 DuMate 生成（2026-09-13）。本地目录曾因克隆中断被清空，文件内容来自 GitHub 远程仓库。