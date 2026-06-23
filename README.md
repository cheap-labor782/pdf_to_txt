# 📄 PDF 轉 TXT 工具

一個純前端、無需伺服器的 PDF 文字提取工具，直接在瀏覽器中將 PDF 檔案轉換為純文字檔 (.txt)。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with PDF.js](https://img.shields.io/badge/Made%20with-PDF.js-blue)](https://mozilla.github.io/pdf.js/)

---

## ✨ 功能特色

- 🔒 **100% 客戶端處理**：所有檔案都在你的瀏覽器內處理，**不上傳任何資料到伺服器**，保障隱私安全
- 📤 **拖曳上傳**：支援點擊選擇或直接拖曳 PDF 檔案
- 🚀 **即時轉換**：快速提取 PDF 中的文字內容
- 🌏 **支援多國語言**：包含中文、英文等 UTF-8 編碼的文字
- 📋 **一鍵複製**：輕鬆複製提取的文字到剪貼簿
- ⬇️ **下載 TXT**：直接儲存為純文字檔 (.txt)
- 📊 **進度顯示**：轉換過程有進度條，清楚掌握處理狀態
- 📱 **響應式設計**：電腦、平板、手機皆可使用

---

## 🖼️ 畫面預覽

![截圖](screenshot.png)

*(你可以放一張實際操作的截圖在這裡)*

---

## 🚀 線上試用

👉 [點此試用](https://你的網址.github.io/pdf-to-txt/) *(請替換為你的 GitHub Pages 網址)*

---

## 🛠️ 技術棧

- **PDF 解析**：[PDF.js](https://mozilla.github.io/pdf.js/) - Mozilla 開發的 PDF 渲染引擎
- **前端框架**：原生 HTML + CSS + JavaScript (Vanilla JS)
- **字型**：微軟正黑體、Consolas
- **部署**：靜態網頁，可部署於 GitHub Pages / Vercel / Netlify 等

---

## 📦 安裝與使用

### 方法一：直接下載使用

1. 下載 `index.html` 檔案
2. 用瀏覽器（Chrome / Edge / Firefox）直接開啟
3. 無需安裝任何軟體，立即使用

### 方法二：部署到 GitHub Pages

```bash
# 1. Clone 專案
git clone https://github.com/你的帳號/pdf-to-txt.git

# 2. 進入目錄
cd pdf-to-txt

# 3. 推送到 GitHub
git add index.html
git commit -m "Initial commit"
git push origin main

# 4. 啟用 GitHub Pages
# 到專案 Settings → Pages → 選擇 main branch → Save
