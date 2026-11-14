# 體驗轉介率計算工具（LALASO）

上傳 Bookfast「團體課表預約明細簽到版」xlsx，依館別（西屯／北屯）與課程（親子／幼兒／兒童）計算每週轉介率。

- 轉介率 = 體驗券（N48、N55、N56）÷ 課程券＋補課券（N02…N25、N71…N82）
- 週別以上課日期計算（週一至週日）
- 以預約計算，不論是否到課；可匯出 CSV
- 檔案只在瀏覽器內處理，不會上傳到任何伺服器
- 票券代碼與課程對應可在頁面下方「計算設定」修改（存在該瀏覽器）

## 部署（GitHub Pages）
1. 新增 repo，上傳 `index.html`
2. Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main` / `(root)`
3. 約 1 分鐘後網址為 `https://<帳號>.github.io/<repo名稱>/`
