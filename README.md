專業分鏡表編輯器 (Cloud Storyboard Editor)

這是一個基於 HTML5、Tailwind CSS 與 Google Apps Script (GAS) 開發的專業分鏡表編輯器。支援雲端儲存、圖片上傳至 Google Drive 以及即時分鏡播放功能。

🚀 功能特點

雲端儲存：與 Google Sheets 同步，隨時隨地存取你的分鏡資料。

圖片整合：支援從剪貼簿貼上圖片或直接上傳，圖片將儲存於 Google Drive。

即時播放器：可根據每一格設定的秒數（Sec）進行分鏡預覽播放。

響應式設計：支援列印模式，可直接輸出 A4 尺寸的分鏡表。

帳號系統：簡易的註冊與登入功能，保護個人作品。

🛠 快速上手

1. 後端部署 (Google Apps Script)

建立一個新的 Google 試算表。

點擊「擴充功能」 > 「Apps Script」。

貼上 backend.gs 的程式碼。

點擊「部署」 > 「新增部署」，選擇「網頁應用程式」。

將「誰有權限存取」設為「所有人」。

複製產生的 webAppUrl。

2. 前端設定

開啟 storyboard_editor.html。

找到 const webAppUrl = "..." 並替換成你的部署網址。

直接在瀏覽器開啟該 HTML 檔案即可使用。

📂 檔案結構

storyboard_editor.html: 前端使用者介面與邏輯。

backend.gs: Google Apps Script 後端邏輯（需部署於 Google 端）。

README.md: 專案說明文件。

📝 授權

本專案採用 MIT 授權條款。
