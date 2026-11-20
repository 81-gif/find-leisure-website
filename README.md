# 闲刻官网

官网静态页面、图片和扩展下载包。无需构建，不包含扩展源码、私钥、访问令牌或后端服务。

## GitHub Pages

仓库 Settings → Pages → Build and deployment：

- Source：Deploy from a branch
- Branch：main
- Folder：/ (root)

页面全部使用相对资源路径，支持项目子路径。`.nojekyll` 保留原始静态文件，无需 Jekyll 构建。

预期访问地址：`https://81-gif.github.io/find-leisure-website/`。只有启用 Pages 且发布成功后才可访问。

扩展下载：`download/find-leisure-0.1.0-chrome.zip`。

## 更新

将扩展主项目 `website/` 中的 `index.html`、`styles.css`、`assets/` 和 `download/` 同步至仓库根目录后提交到 main，Pages 自动重新发布。
