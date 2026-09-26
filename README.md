# 東京旅遊 Tokyo Travel｜東京七日互動行程

2026/11/12（四）～11/18（三）東京七天六夜行程網站。單一 HTML 檔案，不需要安裝或建置，直接用瀏覽器打開 `index.html` 就能用。
線上版：https://austintsao.github.io/Tokyo6D/

## 行程重點
- DAY 1：CI 100 13:30 抵達成田機場 → 飯店入住 → 晚餐 USHIGORO S. GINZA
- DAY 2：麻布台之丘 → teamLab Borderless → 晚餐人形町今半 銀座店
- DAY 3（11/14 六）：豐洲 → 銀座 → 小石川後樂園夜間賞楓 18:00 入場 → 晚餐從簡（飯田橋周邊）
- DAY 4：原宿 → 表參道 → 午餐 Peter Luger（惠比壽）→ SHIBUYA SKY（15:00 入場看夕陽）→ 晚餐牛たんの檸檬 總本店（西新宿）
- DAY 5：池袋 Chiikawa Park → 午餐たかはし拉麵 → 三鷹之森吉卜力美術館（14:00 時段）→ 新宿思出橫丁串燒晚餐
- DAY 6：上野 → 秋葉原 → 兩國 → 淺草寺 → 淺草Rockza 16:10–18:00 場次 → 晚餐
- DAY 7：TOKYO DREAM PARK → 12:30 前出發 → 15:00 前抵達成田機場，搭 CI 105 返台

## 使用方式
1. 打開網站，填入出發日期（共 7 天）、人數和住宿地點，就會產生七天行程。
2. 在「更多 → 設定」輸入 Google Maps API Key，可以啟用真實地圖、路線和餐廳搜尋；沒有金鑰時會用內建示範資料。
3. 天氣使用 Open-Meteo，不需要金鑰。

> Google Maps API Key 只存在瀏覽器的 localStorage，原始碼裡沒有任何金鑰。如果要在公開網站用自己的金鑰，請在 Google Cloud Console 設定「HTTP 參照網址限制」，只允許你的 github.io 網址使用。
