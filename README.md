# Jensen Deng · Personal Academic Portfolio

邓力毓的中英双语学术个人网站。静态 HTML、CSS、JavaScript 项目，无需安装依赖。

## 本地运行

直接双击 `index.html` 即可打开网站。建议使用 VS Code 的 Live Server 扩展预览，但不是必须。

## 网站功能

- 中英文切换（浏览器本地保存语言选择）
- 自适应手机、平板和电脑
- 关于、科研、论文、项目、荣誉、CV、联系栏目
- 邮件联系和 GitHub 跳转
- 无后端、无构建工具、无运行时依赖

## 如何修改

- 个人资料和展示文字：`index.html` 以及 `script.js` 的 `translations` 对象（中英两种都要修改）
- 主题配色、布局、字体：`style.css`
- 链接、邮箱：`index.html`
- 网站图标：`assets/favicon.svg`
- 论文和奖项：目前为待更新面板，取得真实成果后再添加条目
- 简历：将自己的 `cv.pdf` 放入 `assets/`，将 CV 区块中的 `href="#contact"` 改为 `href="assets/cv.pdf"`，可添加 `download` 属性

## 免费部署到 GitHub Pages

1. 在 GitHub 创建公开仓库（例如 `personal-website`）。
2. 上传本项目的 `index.html`、`style.css`、`script.js` 和 `assets/`，注意保持目录结构。
3. 进入仓库 Settings → Pages。
4. 在 Build and deployment 选择 Deploy from a branch；选择 `main` 和 `/ (root)`，保存。
5. 页面发布后，地址通常为 `https://SeattleVermilion.github.io/personal-website/`（实际以 GitHub Pages 显示为准）。

如需使用 `https://SeattleVermilion.github.io/` 根网址，可将仓库命名为 `SeattleVermilion.github.io`。

## 真实内容说明

音乐分类和多模态评测仅作为已提及的项目/调研方向展示；未声称有已发表论文、获奖结果或可下载 CV。个人简介目前是可修改的占位介绍。

## 隐私提醒

部署公开网站前请确认愿意公开姓名、学校和邮箱。所有写入网页的内容都可以被访问者查看。


## Image assets

- `assets/tech-avatar.jpg`: hand-drawn profile avatar for tech mode
- `assets/academic-avatar.jpg`: portrait photo for academic mode
- The previous About photo has been removed from the website and distribution.


## Themes

Use the theme button in the top navigation to switch between Tech and Academic modes. Language and theme choices are saved separately in the browser. To edit colors, use the `body[data-theme="academic"]` rules at the bottom of `style.css`.


## 中国内地访问优化版 / Mainland-friendly edition

- 已移除 Google Fonts 远程字体依赖，使用系统字体；在中国大陆和海外均不再需要额外连接 Google 字体服务。
- 保留科技风手绘头像 `assets/tech-avatar.jpg` 和学术风真人头像 `assets/academic-avatar.jpg`，学术头像做了无损尺寸缩小及有损 JPEG 体积优化。
- 头像始终本地托管，不调用第三方图片 CDN；主题切换和中英文切换仍由 `script.js` 完成。
- GitHub Pages 自身在中国内地可能不稳定；以上优化减少外部请求，但**不保证**跨境网络畅通。

### 更新已上线的网站

将本压缩包解压后，把 `index.html`、`style.css`、`script.js`、`README.md` 和 `assets/` 中的文件上传到现有 GitHub 仓库 `SeattleVermilion.github.io` 的根目录，替换同名文件，然后提交修改。**不要再创建仓库、修改 DNS 或重新绑定域名**。部署完成后访问 https://jensendeng.com 并强制刷新（Windows 可用 Ctrl+F5）。
