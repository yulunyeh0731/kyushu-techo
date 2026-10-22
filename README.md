# 九州旅手帖 2026秋

11/20–11/25 九州一人旅行程 App（PWA）。

## 檔案
- `index.html`：行程網頁本體
- `manifest.webmanifest`：App 名稱、圖示、開啟方式
- `sw.js`：離線快取
- `icons/`：App 圖示

## 上傳到 GitHub Pages
1. 在 GitHub 建立新的儲存庫（Repository），名稱自訂，例如 `kyushu-techo`，設為 Public。
2. 把這個資料夾裡的所有檔案（含 `icons` 資料夾）上傳到儲存庫根目錄。
3. 到儲存庫的 Settings → Pages，Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 等一兩分鐘，網址會是 `https://你的帳號.github.io/kyushu-techo/`。
5. 頁面已設定不讓搜尋引擎收錄，只有拿到網址的人才找得到。

## 加到手機主畫面
- iPhone：用 **Safari** 打開網址 → 分享 → 加入主畫面。
- Android：用 **Chrome** 打開網址 → 選單 → 加到主畫面（或安裝應用程式）。
- 加好後，在有網路的地方打開一次，之後沒網路也能看行程。點地名開 Google 地圖仍需要網路。
- iPhone 在 Safari 打的勾和主畫面 App 打的勾是分開保存的，建議只用主畫面 App。

## 修改內容
1. 修改 `index.html`。
2. 打開 `sw.js`，把第一行的 `kyushu-techo-v1` 改成 `kyushu-techo-v2`（之後每次改都加 1）。
3. 兩個檔案一起上傳。朋友在有網路時打開 App，就會更新成新版本（有時要關掉再開一次）。

## 直接打開某一天
網址後面加上代號：`#d1`～`#d6`（11/20～11/25）、`#transit`（交通）、`#koyo`（紅葉）、`#list`（清單）。
