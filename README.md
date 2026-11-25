# 學習冒險島｜初中篇

GitHub 網頁上傳簡易版。網站檔案全部放在 repository 最外層，沒有 dist、assets 或隱藏資料夾；使用中的兩張像素圖片與 HTML、CSS、JavaScript 放在同一層，請一併上傳。

## 上傳及發布

1. 解壓 ZIP，打開 github-easy-upload 資料夾。
2. 在 GitHub repository 最外層選 Add file → Upload files。
3. 選取本資料夾內全部 10 個檔案上傳，不要上傳 ZIP 或外層資料夾。
4. 若已有同名 README.md，可一併取代。
5. 到 Settings → Pages，Source 選 Deploy from a branch。
6. Branch 選 main，資料夾選 / (root)，按 Save。
7. 等待部署完成，從 Pages 設定頁開啟網站。

若曾上傳舊版 dist，可刪除它；若曾加入 .github/workflows/pages.yml，請刪除該舊工作流程，以免它繼續部署舊的 dist。

## 本機預覽

在本資料夾執行 python3 -m http.server 8000，再開啟 http://localhost:8000 。無須安裝 npm 套件或編譯。

## 功能與資料

保留原有議論文教學、闖關介面、提示、列印與文字匯出功能。其他科目及文體尚未開放；自訂腦圖為手動填寫，目前沒有 AI 連接。

暱稱、筆記與進度只儲存在目前瀏覽器的 localStorage，沒有真正帳戶或雲端同步。更換裝置、瀏覽器、網站網域或清除網站資料後，不會自動保留舊紀錄，請先匯出作品。完成印記不是寫作能力評分。

來源提交：b781b43b3329adcc2a47e4286be3b080e7cd599e。整理日期：2026-11-26。
本包未指定開源授權。
