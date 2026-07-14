# iOS 开发笔记

这是一个使用 [Quarto](https://quarto.org/) 管理并发布到 GitHub Pages 的静态网站。

## 本地预览

安装 Quarto 后，在项目根目录运行：

```bash
quarto preview
```

生成静态站点：

```bash
quarto render
```

生成结果位于 `_site/`。推送到 `main` 分支后，GitHub Actions 会自动构建并发布到 `gh-pages` 分支。

## 添加文章

新建语义化命名的 `.qmd` 文件（例如 `swiftui-grid.qmd`），并把它加入 `_quarto.yml` 的导航栏。Quarto 会统一处理主题、目录、代码高亮和页面布局。
