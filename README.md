# RED LEDGER｜赤紅帳本

## 專案內容
- `index.html`：記帳網站
- `manifest.webmanifest`：PWA 安裝設定
- `sw.js`：離線快取
- `icon.svg`：網站與主畫面圖示

## 用 GitHub Pages 免費發布
1. 登入 GitHub，建立一個新的 **Public** repository，例如 `red-ledger`。
2. 將本資料夾內四個網站檔案（`index.html`、`manifest.webmanifest`、`sw.js`、`icon.svg`）上傳到 repository 根目錄。
3. 進入 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選 `main`、資料夾選 `/(root)`，按 Save。
6. 等待部署完成，GitHub Pages 會提供網址，通常是 `https://你的帳號.github.io/red-ledger/`。

## iPhone Safari 加到主畫面
1. 用 Safari 開啟 GitHub Pages 網址。
2. 點分享按鈕（方框向上箭頭）。
3. 選「加入主畫面」。
4. 名稱可設為「赤紅帳本」，再按「加入」。

## 資料保存提醒
交易資料使用瀏覽器 `localStorage`，資料留在目前瀏覽器/裝置。請定期使用網站內的「匯出 JSON 備份」。不要清除 Safari 網站資料，除非已經備份。GitHub Pages 只託管網站程式，不會讀取或備份你的私人交易紀錄。
