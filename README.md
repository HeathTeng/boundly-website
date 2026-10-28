# getboundly.com

Boundly 的官网，单个 `index.html`（内嵌 CSS 和原生 JS，中英切换），用 GitHub Pages 发布：推送到 `main` 就上线。

- 外观和 Bridgeboard 面板一致：浅绿底、三块淡光斑、圆角玻璃卡片，深绿只用在 Bridgeboard 那张大卡片上。
- 首屏是 Bridgeboard（你的专属 Blackboard 看板），两个下载按钮指向 [HeathTeng/Bridgeboard](https://github.com/HeathTeng/Bridgeboard) 最新版本里的 `Bridgeboard-Windows.zip` 和 `Bridgeboard-Mac.zip`（Mac 是试用版，浅色描边的那个），以后发新版不用改网站。手机、平板和 Linux 上会看到「请在电脑上打开」的提示。
- 往下是 Boundly 的构想、Bridgit 原型和「我们守住的边界」。
- 首屏右边是可以横向滑动的截图，会每 5 秒自动翻一张（鼠标放上去或手动滑动时停下）。`assets/` 里的截图用 Bridgeboard 示例模式（`demo.bat`）截取，不含真实数据（现在 6 张，v0.3.2）。
- 访问统计用 Umami（无 cookie）：下载按钮、GitHub 链接、订阅、邮件链接带 `data-umami-event`，页脚有说明。
- 联系：hello@getboundly.com · Bridgeboard 反馈：feedback@getboundly.com
