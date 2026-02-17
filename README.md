# GitHub Pages 发布包（iOS 友好）

你有两种发布方式（任选其一）：

## 方式 1：从仓库根目录发布（推荐）
1) 上传根目录里的 `index.html`（以及 `404.html`、`.nojekyll`）
2) GitHub 仓库 Settings → Pages
3) Source: Deploy from a branch
4) Branch: main
5) Folder: /(root)

打开生成的链接：`https://<用户名>.github.io/<仓库名>/`

## 方式 2：从 docs 目录发布（如果你更习惯 docs）
1) 保留本包的 `docs/` 文件夹整体上传
2) Settings → Pages
3) Folder 选择 `/docs`

> iOS：用 Safari 打开链接后 → 分享 → “添加到主屏幕”，即可像 App 一样全屏使用。
