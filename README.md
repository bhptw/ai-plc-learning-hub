# AI × PLC 工業自動化互動學習平台

本網站由 8 份獨立 HTML 互動教材與一個整合入口頁組成，適用 GitHub Pages 靜態部署。

## 部署方法
1. 建立新的公開 GitHub Repository（建議：`ai-plc-learning-hub`）。
2. 將此資料夾**內部的全部檔案**上傳至 Repository 根目錄（`index.html` 必須在根目錄）。
3. GitHub Repository → Settings → Pages → Build and deployment → Deploy from a branch。
4. 選擇 `main` / `/(root)` → Save；待 GitHub 顯示已部署後，開啟網站網址。
5. 若使用者帳號為 `YOUR-USERNAME`、Repository 名稱為 `ai-plc-learning-hub`，網址通常為 `https://YOUR-USERNAME.github.io/ai-plc-learning-hub/`。

## 網站頁面

| 上傳檔名 | 主題 |
| --- | --- |
| `index.html` | 新建立的整合入口網站 |
| `ai-history-schools.html` | AI 發展脈絡與學派 |
| `ai-industry40-plc-scl.html` | AI × 工業 4.0 × PLC × SCL |
| `factoryio-reverse-learning.html` | Factory I/O 反向學習 |
| `plc-neural-networks.html` | PLC 系統與神經網路 |
| `plc-ai-prompt-framework.html` | PLC × AI Prompt 工程框架 |
| `scl-interactive-course.html` | SCL 入門互動課程 |
| `kmap-learning-map.html` | K-map 互動教學地圖 |
| `kmap-simplification.html` | K-map 消除技巧專章 |

## 版本處理原則
- 8 個教材 HTML 僅更名，沒有更動教材中的 HTML/CSS/JS 或教學內容。
- 原有入口網站 `010_入口網站_工業自動化 ITOT 整合主控台.html` 不直接使用，改成新的 `index.html`，因其指向未提供的子頁與本機 `127.0.0.1:3000` 工具。
- 網站沒有伺服器端程式，教材不需要 Node.js、npm 或資料庫。
- 各頁並未完成所有瀏覽器上的實際互動驗收；已完成 JavaScript 語法檢查與入口連結完整性檢查。
- 教材內容保留原樣；上線前建議另做教學程式碼審查（例如 SCL 第一課的分號）。
