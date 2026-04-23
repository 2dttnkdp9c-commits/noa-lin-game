# Noa Lin's Big Diploma Quest · 苹果安装版（PWA包）

这不是 IPA 安装包，而是适合 iPhone 的 PWA 安装包。

## 正确安装方式
1. 把整个文件夹上传到一个 HTTPS 网站：
   - GitHub Pages
   - Cloudflare Pages
   - Vercel
   - Netlify
2. 用 iPhone 的 Safari 打开上传后的网址
3. 点击“分享”
4. 选择“添加到主屏幕”
5. 主屏幕会出现游戏图标，打开后接近 App 体验

## 为什么不能直接给 IPA
IPA 需要 Xcode / Apple 开发者签名 / 打包发布流程。
当前这个环境可以为你做好 iPhone 适配网页安装版，但不能直接产出已签名 IPA。

## 文件说明
- index.html：游戏入口
- manifest.webmanifest：安装配置
- sw.js：离线缓存
- poster.png：启动页海报
- icons/：主屏幕图标
