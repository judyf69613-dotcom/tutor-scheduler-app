家教排課 App 版（PWA）安裝說明

這是一個可安裝到手機桌面的 Web App，不需要上架 App Store / Google Play。
資料會存在該裝置的瀏覽器中，建議定期在 App 內匯出 JSON 備份。

iPhone / iPad 安裝：
1. 把 tutor_scheduler_app 資料夾上傳到可公開瀏覽的網站，例如 GitHub Pages、Netlify、Vercel 或學校/自己的網頁空間。
2. 用 Safari 開啟 index.html 的網址。
3. 點分享按鈕。
4. 選「加入主畫面」。
5. 之後就能像 App 一樣從桌面開啟。

Android 安裝：
1. 用 Chrome 開啟 index.html 的網址。
2. 點右上角選單。
3. 選「安裝應用程式」或「加入主畫面」。

注意：
- 如果直接用檔案開啟 index.html，也能使用主要功能，但不一定能啟用真正的離線 App 安裝。
- 若要做成 Android APK 或 iPhone App Store 版本，需要再用 Capacitor / Flutter / React Native 封裝。
