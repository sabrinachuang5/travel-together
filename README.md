# Travel Together — 純 GitHub Pages 個人旅遊規劃網站

不使用 Supabase、不需要會員帳號、不需要其他雲端資料庫服務。

## 功能
- 多趟旅行管理
- 每日行程新增、修改、刪除
- 景點與地址可連結 Google Maps 搜尋
- 預算上限、支出紀錄（不同幣別分開統計）
- 飯店、地址、入住退房、訂房編號及備註
- 手機優先響應式介面
- JSON 備份匯出與匯入

## 資料儲存與限制
- 資料存在目前瀏覽器的 localStorage。
- 同一裝置、同一瀏覽器可在重新開啟後繼續使用。
- 不會自動同步到其他裝置，也不會分享給朋友共同編輯。
- 清除網站資料、更換瀏覽器或裝置前，請先使用「備份」下載 JSON 檔。
- 匯入備份會取代目前瀏覽器中的全部旅程，請先匯出現有資料。
- GitHub Pages 公開的是網站程式碼；旅程資料不會上傳到 GitHub。

## 部署到 GitHub Pages
1. 解壓縮此資料夾。
2. 到 https://github.com/new 建立 repository，例如 `travel-together`。
3. 將資料夾內所有檔案上傳到 repository 根目錄，包含 `.github` 資料夾。
4. GitHub repository → Settings → Pages。
5. Build and deployment 的 Source 選擇 **GitHub Actions**。
6. 推送到 `main` 分支後，Actions 會自動部署。
7. 網站網址通常為 `https://USERNAME.github.io/travel-together/`。

## 使用方式
開啟網站後建立旅程，接著新增每日景點、記錄支出、住宿資料。定期到「備份」頁下載 JSON 檔。
