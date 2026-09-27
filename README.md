# h5-release

Official product sites and landing pages.

## Layout

Each product lives in its own folder (folder name = project name):

| Path | Product |
| --- | --- |
| `/THEOL-downloader/` | 课程资源助手（THEOL 课件批量下载） |
| `/m3e-canvas/` | M3E Canvas（Material 3 Expressive 界面草图 → vibe-coding 提示） |

Root `index.html` is a directory of product sites. Add a new product as `/<folder>/` and link it from the root.

## Local preview

Serve this directory as static files and open `/`, `/THEOL-downloader/`, or `/m3e-canvas/`.
