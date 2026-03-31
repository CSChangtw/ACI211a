# ACI 211.1 混凝土配比設計 PWA

## 部署說明 (GitHub Pages)

1. 將此 zip 解壓縮後，把所有檔案上傳至 GitHub repo 根目錄
2. 至 **Settings → Pages → Source** 選擇 `main` branch / `/ (root)`
3. 儲存後約 1-2 分鐘即可透過 `https://<username>.github.io/<repo>/` 存取
4. 首次開啟後瀏覽器會出現「加入主畫面」提示，可安裝為 PWA

## 檔案結構
```
/
├── index.html          主程式 (ACI 211.1 計算引擎)
├── manifest.json       PWA 設定檔
├── sw.js               Service Worker (離線快取)
├── favicon.ico         網頁圖示
├── .nojekyll           停用 Jekyll (必要)
├── README.md           本說明
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```
