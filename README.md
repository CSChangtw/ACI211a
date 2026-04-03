# ACI 211.1 混凝土配比設計 PWA

依據 ACI 211.1 標準之混凝土配比設計計算工具，支援 PWA 安裝。

## 部署至 GitHub Pages

1. 建立 GitHub Repository（例如 `aci211-mix-design`）
2. 將此 zip 解壓縮後，將所有檔案推送至 `main` branch 根目錄
3. 前往 Repository → Settings → Pages → Source 選 `main` branch / `/ (root)`
4. 完成後即可透過 `https://<你的帳號>.github.io/<repo名稱>/` 開啟
5. 在手機瀏覽器開啟後，選「加入主畫面」即可安裝為 App

## 檔案結構

```
/
├── index.html          ← 主程式
├── manifest.json       ← PWA 清單
├── sw.js               ← Service Worker（離線快取）
├── icon.png            ← 主圖示 512x512（根目錄）
├── favicon.ico         ← 瀏覽器分頁圖示
└── icons/
    ├── apple-touch-icon.png  ← iOS 主畫面圖示
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```
