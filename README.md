# h5-release

Official product sites and landing pages.

## Layout

Each product lives in its own folder (folder name = project name):

| Path | Product |
| --- | --- |
| `/THEOL-downloader/` | 课程资源助手（THEOL 课件批量下载） |
| `/m3e-canvas/` | M3E Canvas（Material 3 Expressive 界面草图 → vibe-coding 提示） |
| `/codex-retry-rescue/` | Codex Retry Rescue（Codex 断流/限流/会话死亡自动救援） |

Root `index.html` is a directory of product sites. Add a new product as `/<folder>/` and link it from the root.

`/codex-retry-rescue/` 是构建产物，源码在 [vg188/codex-retry-rescue](https://github.com/vg188/codex-retry-rescue) 的 `site/`（Vite + React + Tailwind，字体随包自托管，运行时零外部请求）。改完跑 `npm run build`，把 `dist/*` 覆盖到本目录。

## Local preview

Serve this directory as static files and open `/`, `/THEOL-downloader/`, or `/m3e-canvas/`.
