# 日日健康 Web App 7.0

這一版不是 ZIP 內直接預覽的 HTML demo，而是重新整理成「可部署到 HTTPS 網站」的 PWA 結構。

使用方式：
1. 將整個資料夾部署到任何支援 HTTPS 的靜態網站。
2. iPhone 用 Safari 開啟網站。
3. 之後可以用 Safari 的「加入主畫面」變成 App 形式。
4. 不要在 iPhone「檔案」App 裡直接預覽 ZIP 測試互動功能。

目前已包含：
- 今日 Dashboard
- 飲食與每日熱量
- 喝水
- 體重／體脂
- 睡眠
- 排便
- SpO₂／心率
- 哮喘紀錄
- 減重目標
- 個人食物資料庫
- 週檢查
- 個人化熱量目標
- AI Proxy 介面
- PWA manifest / service worker

AI：
前端不保存 API Key。AI 健康助手使用 AI Proxy URL。
真正上線時，請把 AI Proxy 部署在 HTTPS 後端，再於「更多 → AI 設定」填入端點。

重要：
目前這個版本可以作為正式 Web App 的前端基礎，但「真正上線」仍需要一個 HTTPS 網域／部署平台。直接雙擊 HTML 不等於正式 Web App。
