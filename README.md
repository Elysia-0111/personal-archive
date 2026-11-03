# 个人网站

这是一个托管在 GitHub Pages 上的课程参考资料与实验索引。用浏览器打开 `index.html` 即可预览。

课程目录是学习计划。仅在本人确认完成某门课并提出更新后，才整理和展示该门课的资料与实验。

每门课在 `courses/` 下有独立页面，以培养方案的课程编号命名。更新时，从课程目录找到对应页面，在「参考资料」小节整理该门课用过的书目、视频与文章，在「实验」小节填写实验简介和 GitHub 链接。

## 发布到 GitHub Pages

1. 在 GitHub 创建仓库。使用免费个人账户时，选择公开仓库。
2. 将本站文件按现有目录结构上传到 `main` 分支，确保仓库首页能直接看到 `index.html`。
3. 在仓库的 **Settings → Pages** 中，将 **Source** 设为 **Deploy from a branch**。
4. 选择 **main** 和 **/ (root)**，点击 **Save**。部署完成后，在同一页面打开网站地址。

此后，提交到 `main` 分支的页面修改会自动发布。详见 [GitHub Pages 发布源配置文档](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)。
