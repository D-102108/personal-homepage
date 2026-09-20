# 邓紫鹃个人主页

这是一个只使用 HTML、CSS 和 JavaScript 制作的静态个人 Portfolio 网站，可直接部署到 GitHub Pages，无需后端服务器。

## 项目结构

```text
index.html
css/style.css
js/main.js
images/image1.jpg
images/image2.jpg
images/image3.jpg
resume/resume.pdf
```

## 如何本地预览

直接双击 `index.html` 即可在浏览器预览。也可以在 VS Code 安装 **Live Server** 扩展后，右键 `index.html`，选择 **Open with Live Server**。

## 如何替换照片

将自己的照片分别替换为 `images/image1.jpg`、`images/image2.jpg` 和 `images/image3.jpg`。请保持文件名和扩展名不变；如使用 PNG 等其他格式，需要同步修改 `index.html` 内对应的图片路径。

## 如何替换 PDF 简历

将新简历命名为 `resume.pdf`，放入 `resume` 文件夹并覆盖原文件。下载按钮已链接到相对路径 `resume/resume.pdf`，无需修改代码。

## 如何上传到 GitHub

1. 在 GitHub 新建一个公开仓库，例如 `personal-homepage`。
2. 将本项目文件夹中的全部文件上传到仓库根目录。
3. 在仓库页面确认能看到 `index.html`、`css`、`js`、`images` 和 `resume`。

也可以使用 Git：

```bash
git init
git add .
git commit -m "Create personal homepage"
git branch -M main
git remote add origin https://github.com/你的用户名/personal-homepage.git
git push -u origin main
```

## 如何开启 GitHub Pages

1. 进入 GitHub 仓库，打开 **Settings** → **Pages**。
2. 在 **Build and deployment** 中选择 **Deploy from a branch**。
3. Branch 选择 `main`，文件夹选择 `/(root)`，点击 **Save**。
4. 等待约一分钟，GitHub 会显示公开网址，通常是 `https://你的用户名.github.io/personal-homepage/`。
5. 使用未登录浏览器窗口打开该网址，确认照片、页面导航和简历下载均正常。

所有站内资源均为相对路径，因此上传后可直接用于 GitHub Pages。
