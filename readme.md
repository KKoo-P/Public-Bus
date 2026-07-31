🚌 HK Bus Express - 香港九巴及城巴即時路線網頁 (HK Bus Live ETA & Fares)

A modern, responsive, and bilingual Progressive Web App (PWA) for querying real-time Hong Kong bus routes, bus stops, live arrival ETAs, and fare information for KMB (九巴) and Citybus (城巴).

一款響應式、雙語的香港公共巴士即時路線與到站時間（ETA）網頁應用程式，整合九巴與城巴全港路線數據、動態地圖、全程與分段車費顯示、GPS 精準定位及 PWA 離線安裝支援。

✨ Features / 功能特點

⚡ All Hong Kong Bus Routes (全港路線動態載入): Connects to DATA.GOV.HK, KMB, and Citybus APIs to fetch hundreds of official routes across HK Island, Kowloon, New Territories, and Cross-Harbour routes.

💳 Fare Information (車費數據顯示): Displays full fares on route cards and detail headers, plus sectional fares (分段車費) for each individual bus stop along the timeline and map popups.

🌐 Dynamic Bilingual Support (全動態雙語轉換): Toggle seamlessly between 繁體中文 (Traditional Chinese) and English. Interface text, route names, stop markers, popups, map headers, region controls, and legends all update instantly.

🗺️ Fixed Day-Mode Map (固定日間地圖): Uses CartoDB Voyager light tiles at all times for maximum contrast and legibility, regardless of whether the UI theme is in Dark or Light mode.

📍 Precise GPS Geolocation (精準 GPS 位置定位): Prompts for browser permission to accurately pinpoint user location on the interactive map with a pulse marker and accuracy halo.

📱 PWA Ready (PWA 獨立應用程式): Includes manifest.json and sw.js (Service Worker), enabling users to install the web application directly on iOS, Android, or Desktop.

🛡️ Graceful Offline Fallback (備用數據機制): Built-in notification toasts and mock datasets ensure the app remains fully functional even if external APIs face network CORS or latency issues.

📁 Repository Structure / 檔案結構

.
├── index.html        # Main Application File (HTML5, Tailwind CSS, Leaflet JS, Logic)
├── manifest.json     # PWA Manifest Configuration
├── sw.js             # Service Worker for Offline Caching & API Network Strategies
└── README.md         # Project Documentation

Access Your Live Web App: Within 1–2 minutes, your live site will be accessible at:
https://kkoo-p.github.io/Public-Bus/

🛠️ Built With / 技術棧

HTML5 & JavaScript ES6+

Tailwind CSS CDN - Utility-First Styling

Leaflet.js - Interactive Map Framework

CartoDB Voyager Tiles - Daytime Basemap Layer

DATA.GOV.HK APIs - Official Transport Open Data

📄 Data Sources & Disclaimer / 數據來源及聲明

Bus route information, stop locations, and ETA timings are powered by open data provided by the Government of Hong Kong (DATA.GOV.HK), KMB, and Citybus. This project is open-source and intended for reference purposes only.