# WenPo 隐私与支持网站

这是可直接用于 GitHub Pages 的静态网站，无需安装依赖或运行构建命令。

将**本目录内的文件和文件夹**复制到你的 GitHub 网站仓库根目录，使仓库保持以下结构：

```text
index.html
styles.css
favicon.svg
privacy/index.html
support/index.html
```

然后在该仓库的 **Settings → Pages** 中选择 **Deploy from a branch**、发布分支和 **/(root)**。GitHub Pages 发布后，首页为仓库的网站地址；隐私政策与支持页分别在该地址后加 `/privacy/` 和 `/support/`。把这两个完整的 HTTPS 地址分别填入 App Store Connect 的 Privacy Policy URL 和 Support URL。

网站使用相对链接，因此用户网站（`用户名.github.io`）和项目网站（`用户名.github.io/仓库名`）都可使用。发布前检查页面中的邮箱 `chiuyan.ning@gmail.com` 与政策内容是否仍符合当前 App 版本。
