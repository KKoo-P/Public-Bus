🚌 HK Bus Express - 香港九巴及城巴即時路線網頁 (HK Bus Live ETA)

A modern, responsive, and bilingual Progressive Web App (PWA) for checking real-time Hong Kong bus routes, stops, live arrival ETAs, and fare information for KMB (九巴) and Citybus (城巴).

一款響應式、雙語的香港公共巴士即時路線與到站時間（ETA）網頁應用程式，支援九巴與城巴路線數據、動態地圖、車費顯示及 PWA 安裝。

✨ Features / 功能特點

⚡ Real-Time Bus ETA (即時到站時間): Live arrival countdown powered by DATA.GOV.HK and bus operator APIs.

💳 Fare Information (車費數據顯示): Clear display of full fares and sectional fares across route lists, timelines, and interactive map popups.

🌐 Dynamic Bilingual Support (全動態雙語轉換): Toggle seamlessly between 繁體中文 (Traditional Chinese) and English. All interface text, route destinations, stop names, tooltips, map popups, and legends update dynamically without refreshing.

🗺️ Interactive Leaflet Map (互動式地圖): Displays route traces and bus stop markers. Maintained in Day Mode at all times for maximum readability and optimal contrast.

🌓 Theme Mode (日夜間模式): UI supports both Light Mode and Dark Mode for comfortable viewing in any environment.

🌟 Favorites System (收藏功能): Save frequently used bus routes to local storage for quick access.

📱 PWA Ready (PWA 獨立應用程式): Includes manifest.json and sw.js (Service Worker) allowing users to install the web app on iOS, Android, or Desktop with offline asset caching.

🛡️ Graceful API Fallback (備用數據機制): Automatically switches to demo fallback dataset if external API requests encounter network latency or CORS restrictions.

📁 Repository Structure / 檔案結構

├── index.html        # Main Application File (HTML5, Tailwind CSS, Leaflet JS, Logic)
├── manifest.json     # Progressive Web App (PWA) Manifest File
├── sw.js             # Service Worker for Offline Caching & Network First Strategy
└── README.md         # Project Documentation


🚀 How to Deploy on GitHub Pages / 部署步驟

Upload Files: Upload index.html, manifest.json, and sw.js into your GitHub repository root folder.

Enable GitHub Pages:

Navigate to Settings > Pages in your GitHub repository.

Under Build and deployment > Branch, select main (or master) branch and / (root).

Click Save.

Access Your App: After 1-2 minutes, your live site will be available at https://<your-username>.github.io/<your-repository-name>/.

🛠️ Built With / 使用技術

HTML5 & JavaScript (ES6+)

Tailwind CSS CDN - Utility-first CSS Framework

Leaflet.js - Open-source JavaScript library for interactive maps

CartoDB Voyager Tiles - Clean & crisp map tile layer

DATA.GOV.HK APIs - Hong Kong Government Data OneStop

📄 License / 條款與聲明

This project is open source and created for transportation reference only. Bus data is sourced from open APIs on DATA.GOV.HK, KMB, and Citybus.