# Remove 91pu Ads Chrome Extension

## 簡介

這是一個針對 91譜 ( https://www.91pu.com.tw ) 網站的 Google Chrome 擴充程式，旨在去除該網站每次載入頁面時出現的廣告。這可以提供使用者更乾淨、無廣告的瀏覽體驗。

## 安裝方式

1. 下載擴充程式的 ZIP 檔案或使用 Git 克隆整個存儲庫到本地端。

    ```bash
    git clone https://github.com/your-username/remove-91pu-ads.git
    ```

2. 在 Chrome 瀏覽器中打開擴充管理頁面，進入 `chrome://extensions/`。

3. 啟用「開發人員模式」。

4. 點擊「載入未封裝」並選擇擴充程式所在的文件夾。

5. 完成安裝。

## 使用方式

一旦擴充程式安裝成功，它將自動在每次載入 91譜 網站的頁面時運行，去除廣告。

## 檔案結構

- **manifest.json**: Chrome 擴充程式的清單文件，包含了擴充程式的基本資訊、權限、內容腳本等設定。

- **content.js**: 實際執行去廣告操作的 JavaScript 腳本。

- **icon.png**: 用於擴充程式圖示的圖片。

## 注意事項

- 本擴充程式僅針對 91譜 網站，不保證在其他網站上的運作。

- 由於瀏覽器安全性限制，擴充程式可能無法運作於一些特殊情況下的廣告載入方式。如果遇到問題，請確保您使用的是最新版本的 Chrome 瀏覽器。

## 貢獻

如果您發現擴充程式有問題或有改進的建議，歡迎提交 Issue 或 Pull Request。任何形式的貢獻都將不勝感激。
