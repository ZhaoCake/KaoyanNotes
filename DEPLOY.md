# GitHub Pages 部署说明

这个仓库使用 `Docsify`，不需要构建步骤，直接部署仓库静态文件即可。

## 1. 推送到 GitHub

把当前仓库推送到 GitHub。

## 2. 开启 GitHub Pages

在仓库页面打开：

`Settings` -> `Pages`

然后选择：

- **Source**: `Deploy from a branch`
- **Branch**: `main`
- **Folder**: `/ (root)`

保存后等待 GitHub Pages 发布。

## 3. 访问站点

发布完成后，站点地址通常为：

`https://你的用户名.github.io/仓库名/`

## 4. 后续新增内容

后续如果新增：

- `408/`
- `English/`
- `Politics/`

只需要：

1. 把 Markdown 文件放进对应目录
2. 更新 `_sidebar.md`

## 5. 本地预览

如果只是快速看效果，可以安装 Docsify CLI 后本地预览：

- `npm i -g docsify-cli`
- `docsify serve .`

然后访问本地地址查看。

> 这一步不是必须，GitHub Pages 可以直接托管当前仓库内容。
