# 微信刮刮乐抽奖页

这个目录里已经有一个完整的静态页面：`index.html`。

## 本地预览

直接双击 `index.html` 就能在浏览器里打开预览。

## 生成微信可点击链接

微信里能点击的链接必须是公网 `https://` 地址。最简单的方式：

1. 打开 https://app.netlify.com/drop
2. 把整个 `D:/surprise` 文件夹拖进去
3. 等上传完成后，Netlify 会生成一个 `https://...netlify.app` 链接
4. 把这个链接发给对方，微信里就可以直接点开

也可以用 Vercel、GitHub Pages、Cloudflare Pages 等静态网站托管服务。

## 修改奖品文案

在 `index.html` 里搜索 `const prizes = [`，可以修改礼物名称和描述。
