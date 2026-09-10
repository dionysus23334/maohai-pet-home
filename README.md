# 毛孩小栈

哈尔滨家庭宠物寄养展示网站，使用 HTML、CSS 和 Vite。

## 本地开发

使用 Node.js 22，运行 `npm ci` 和 `npm run dev`。

## 发布

运行 `npm run build`，静态网站输出到 `dist/`。

GitHub 仓库 Settings → Pages → Source 选择 GitHub Actions。
推送至 `main` 后，自动构建并部署到：
https://dionysus23334.github.io/maohai-pet-home/

## 预约联系方式

目前预约按钮显示说明弹窗，尚未接入电话、微信或在线预约服务。
补充联系方式时，修改 `index.html` 的 `booking` 弹窗。
