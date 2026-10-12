# Zhuoyi Cui Resume Website

这是可以直接部署到 GitHub Pages 的静态网站，无需安装软件或编译。
保留当前网站的姓名样式和 Resume 标签。PDF 使用你提供的 2026-10-06 简历；如果你已有新版，先用新版替换 resume.pdf。

## 首次部署

1. 登录 GitHub，创建公开仓库，名称为 YOUR_USERNAME.github.io（替换为自己的 GitHub 用户名）。若该仓库已存在，请使用现有仓库，避免覆盖已有网站。
2. 解压文件包，把 index.html、styles.css、favicon.svg、resume.pdf 和 README.md 上传到仓库根目录。不要上传 ZIP 文件，也不要把外层文件夹一起上传。
3. 点击 Commit changes，提交到 main 分支。
4. 打开 Settings → Pages，在 Source 选择 Deploy from a branch，Branch 选择 main，Folder 选择 /(root)，点击 Save。
5. 等待发布，页面网址为 https://YOUR_USERNAME.github.io/，PDF 地址为 https://YOUR_USERNAME.github.io/resume.pdf。

## 更新简历

1. 在本地完成新版 PDF，并改名为 resume.pdf。
2. 在仓库根目录选择 Add file → Upload files，上传新版同名文件。
3. 选择直接提交到 main，点击 Commit changes。
4. 等待自动发布，原来的网页和 PDF 链接保持不变。
5. 若看到旧版本，刷新页面，必要时强制刷新或用隐私窗口检查。

## 编辑页面

修改 index.html 可调整文字；修改 styles.css 可调整字体、颜色与布局。提交后自动发布。
GitHub 上传操作就是更新入口，本版本没有单独的 /admin 页面。

官方说明：
- https://docs.github.com/en/pages/quickstart
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
