# 🚽 马桶闹钟 (Toilet Alarm)

一个必须走到马桶前才能关闭的闹钟！

## 原理

1. 设定闹钟时间
2. 生成专属 QR Code，打印贴在马桶旁边
3. 闹钟响起后，必须用摄像头扫描到那个 QR Code 才能关闭

再也不会按掉闹钟继续睡了！

## 使用方式

直接在浏览器打开 `toilet-alarm.html` 即可使用。

推荐部署到 GitHub Pages / Vercel / Netlify，然后在手机浏览器中打开，添加到主屏幕作为 PWA 使用。

## 技术栈

- 纯前端单文件 HTML
- PWA (Progressive Web App)
- QR Code 生成与扫描
- Web Audio API 闹钟音效
- 摄像头实时扫描

## 文件说明

- `toilet-alarm.html` - 主应用
- `manifest.json` - PWA 应用清单
- `sw.js` - Service Worker（离线缓存）
- `icon-192.jpg` / `icon-512.jpg` - 应用图标
