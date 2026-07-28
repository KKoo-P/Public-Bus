🚌 HK Bus Express (香港即時巴士指南 PWA)

HK Bus Express 是一個高效、響應式的 Progressive Web App (PWA)，支援香港九巴 (KMB) 及城巴 (Citybus) 的即時到站時間 (ETA) 查詢、路線搜尋、動態地圖軌跡繪製，以及 GPS 精準位置檢測。

🌟 功能特色 (Key Features)

⚡ 即時到站預測 (Live ETA)：直接串接香港政府開放數據 API (DATA.GOV.HK)，提供精準巴士班次倒數。

📍 精準 GPS 定位 (Precise Geolocation)：一鍵獲取當前位置，在地圖上標示並自動計算與各巴士站點的距離。

🗺️ 動態互動地圖 (Interactive Leaflet Map)：繪製巴士路線行車軌跡與站點標記，支援點擊快速地圖導航。

📲 PWA 支援 (Progressive Web App)：支援「加入主畫面 (Add to Home Screen)」，可作為 Native App 獨立開啟，具備 Service Worker 離線快取能力。

🌐 雙語介面 (Bilingual Support)：完整支援繁體中文及英文切換。

🌙 深色/淺色模式 (Dark / Light Theme)：根據系統偏好自動適應，並支援手動切換。

⭐ 路線收藏 (Favorites)：本機儲存常用路線，方便快速查閱。

📁 檔案結構 (File Structure)

.
├── index.html       # 應用程式主頁面 (HTML5 + Tailwind CSS + Leaflet JS)
├── manifest.json    # PWA 清單檔案 (描述 App 名稱、主題色、圖示)
├── sw.js            # Service Worker 腳本 (離線快取與網路策略)
├── icon-192.png     # PWA 圖示 (192x192)
├── icon-512.png     # PWA 圖示 (512x512)
└── README.md        # 專案說明文件


🚀 如何部署至 GitHub Pages (Deployment Guide)

建立 GitHub 儲存庫 (Repository)：

開啟 GitHub，建立一個新的公開 Repository（例如 hk-bus-express）。

上傳專案檔案：

將 index.html、manifest.json、sw.js、README.md 上傳至儲存庫的根目錄 (root)。

(可選) 上傳 icon-192.png 與 icon-512.png 圖片作為 App 圖示。

啟用 GitHub Pages：

進入 Repository 的 Settings ➔ Pages。

在 Source 選項中選擇 Deploy from a branch。

Branch 選擇 main (或 master) / /(root)，然後點擊 Save。

存取 PWA 網站：

約 1~2 分鐘後，您的網站即可透過 https://<your-github-username>.github.io/hk-bus-express/ 存取。

由於 GitHub Pages 提供免費的 HTTPS 連線，GPS 定位與 PWA 安裝功能均可順暢運行。

📲 如何安裝為 App (PWA Installation)

iOS (Safari)：點擊底部「分享」按鈕 ➔ 選擇「加入主畫面 (Add to Home Screen)」。

Android (Chrome)：點擊右上角三點選單 ➔ 選擇「安裝應用程式」或「加入主畫面」。

電腦端 (Chrome / Edge)：網址列右側會出現「安裝」圖示，點擊即可開啟獨立視窗。

📡 API 資料來源 (Data Sources)

DATA.GOV.HK (香港政府資料一線通)

九龍巴士 (KMB) Open API

城巴 (Citybus) Open API

📄 授權條款 (License)

本專案採用 MIT License 授權。