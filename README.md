# 个人网站

这是一个可以托管在 GitHub Pages 上的静态网站。用浏览器打开 `index.html` 即可预览首页，再通过导航访问各个栏目。后续可直接编辑对应页面，逐步补充个人介绍、作品与文字。

## 发布到 GitHub Pages

1. 在 GitHub 创建仓库。使用免费个人账户时，选择公开仓库。
2. 将本站文件按现有目录结构上传到 `main` 分支，确保仓库首页能直接看到 `index.html`。
3. 在仓库的 **Settings → Pages** 中，将 **Source** 设为 **Deploy from a branch**。
4. 选择 **main** 和 **/ (root)**，点击 **Save**。部署完成后，在同一页面打开网站地址。

此后，提交到 `main` 分支的页面修改会自动发布。详见 [GitHub Pages 发布源配置文档](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)。
