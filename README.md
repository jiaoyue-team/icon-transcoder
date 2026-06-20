# Icon 轉碼器 (Icon Converter)

這是一個基於 Node.js 與 Electron 開發的跨平台桌面應用程式。它可以讓您輕鬆地將 `SVG` 格式的向量圖檔轉換為多種尺寸的 `PNG` 圖示，並自動為您打包成單一 `ZIP` 壓縮檔。

## ✨ 核心特色

- **一鍵轉檔打包**：將上傳的 SVG 檔案，轉換為常見的應用程式/網頁圖示尺寸 (`16x16`, `32x32`, `48x48`, `128x128` px)，並自動壓縮為 ZIP 檔。
- **現代化設計**：具備深色模式、毛玻璃效果 (Glassmorphism) 以及流暢的微動畫，提供高質感的視覺體驗。
- **直覺的操作介面**：支援拖曳檔案 (Drag-and-drop) 或是傳統的點擊瀏覽檔案上傳。
- **離線可用**：核心轉換邏輯完全在本地端執行，確保您的圖檔隱私且無須依賴網路。

## 🚀 技術堆疊

- **前端**：HTML5, CSS3 (原生語法), JavaScript
- **後端 (桌面視窗)**：[Electron](https://www.electronjs.org/)
- **影像處理引擎**：[sharp](https://sharp.pixelplumbing.com/) (高效能 Node.js 影像處理庫)
- **壓縮工具**：[archiver](https://www.archiverjs.com/)

## 🛠️ 安裝與啟動

1. 確保您的電腦已安裝 [Node.js](https://nodejs.org/)。
2. 透過命令提示字元或終端機進入本專案資料夾。
3. 安裝必要套件：
   ```bash
   npm install
   ```
4. 在開發模式下啟動應用程式：
   ```bash
   npm start
   ```

## 📦 打包與編譯 (.exe)

本專案使用 `electron-packager` 作為打包工具。若您希望將此應用程式編譯為可以直接執行的 `.exe` 檔，請執行以下指令：

```bash
npm run build
```

編譯完成後，您可以在專案目錄下的 `dist/Icon 轉碼器-win32-x64/` 資料夾中找到 `Icon 轉碼器.exe`。

## 📄 授權

本專案遵循 ISC 授權條款。
