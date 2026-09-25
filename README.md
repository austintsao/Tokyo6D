# Tokyo 6D｜東京六日遊互動行程

單一 HTML 檔案的東京六日遊行程網站，不需要安裝或建置，直接用瀏覽器打開 `index.html` 就能用。

## 行程重點
- DAY 1：麻布台之丘 → teamLab Borderless → 晚餐 USHIGORO S. GINZA
- DAY 2：豐洲 → 銀座 → 晚餐人形町今半 銀座店 → 小石川後樂園夜間點燈（2026/11/13–11/24）
- DAY 3：原宿 → 表參道 → 午餐 Peter Luger（惠比壽）→ SHIBUYA SKY（15:00 入場看夕陽）
- DAY 4：池袋 Chiikawa Park → 午餐たかはし拉麵 → 新宿 → 晚餐牛たんの檸檬 總本店（週一公休）
- DAY 5：上野 → 秋葉原 → 兩國 → 淺草
- DAY 6：TOKYO DREAM PARK → 羽田機場，搭傍晚班機返台

## 使用方式
1. 打開網站，填入出發日期、人數和住宿地點，就會產生六天行程。
2. 在「更多 → 設定」輸入 Google Maps API Key，可以啟用真實地圖、路線和餐廳搜尋；沒有金鑰時會用內建示範資料。
3. 天氣使用 Open-Meteo，不需要金鑰。

## 發佈到 GitHub Pages
到 Repository 的 Settings → Pages，Source 選「Deploy from a branch」，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。約 1 分鐘後網址會是 `https://<你的帳號>.github.io/<repo 名稱>/`。

> Google Maps API Key 只存在瀏覽器的 localStorage，原始碼裡沒有任何金鑰。如果要在公開網站用自己的金鑰，請在 Google Cloud Console 設定「HTTP 參照網址限制」，只允許你的 github.io 網址使用。
