# 智慧 OCR 辨識神器 (PWA)

這是一個完整符合 PWA (Progressive Web App) 標準規範的離線文字辨識應用，內建 Tesseract.js 引擎、多語系支援與專業影像前處理管線。

## 專案結構
- `index.html`: 主應用介面，包含影像增強、二值化、旋轉、微調與辨識邏輯。
- `manifest.json`: Web App Manifest，定義桌面/手機獨立安裝標準。
- `sw.js`: Service Worker 快取腳本，支援離線執行。
- `icon-192.png`: 192x192 標誌圖示。
- `icon-512.png`: 512x512 標誌圖示。
- `.github/workflows/deploy.yml`: GitHub Actions 自動部署腳本。
