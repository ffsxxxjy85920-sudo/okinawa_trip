# 沖繩 5 天 4 夜｜GitHub Pages 版本

旅行日期：2026/10/10–2026/10/14

## 最快上線方式

1. 登入 GitHub。
2. 建立一個新的 **Public repository**，例如：`okinawa-trip-2026`
3. 把這個資料夾內的檔案全部上傳到 repository 根目錄：
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon.svg`
   - `.nojekyll`
4. 進入該 repository：
   **Settings → Pages**
5. 在 **Build and deployment** 設定：
   - Source：`Deploy from a branch`
   - Branch：`main`
   - Folder：`/ (root)`
6. 按 **Save**
7. GitHub Pages 部署完成後，網址通常會是：

   `https://你的GitHub帳號.github.io/okinawa-trip-2026/`

把這個網址貼到 LINE 群組，就可以讓同行者直接開啟。

## 已包含

- 5 天每日行程
- 10/12 方案一 / 方案二切換
- Google Maps 導航
- 網頁分享功能
- 出發前勾選清單（localStorage）
- 手機版 App 介面
- PWA manifest
- Service Worker 離線快取
- App 圖示
- GitHub Pages 相對路徑設定
- `.nojekyll`
- 首里城 2026/11/23 正殿內部公開提醒

## 更新行程

之後只要修改 `index.html` 並 commit / upload 到 `main`，
GitHub Pages 就會自動重新部署。

## 手機加入主畫面

網站上線後，可使用手機瀏覽器的「加入主畫面」功能，
讓它看起來更像獨立旅行 App。

## 注意

航班、營業時間、餐廳預約與交通狀況可能變更，
出發前請以航空公司、景點與店家官方資訊為準。
