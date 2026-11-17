# 🍱 午餐轉盤

不知道午餐吃什麼？打開網頁、找附近店家、轉一下轉盤讓命運決定！

## 功能
- **地圖**：OpenStreetMap + Leaflet，可用 GPS 定位、輸入地址，或直接點地圖設定位置
- **搜尋附近店家**：可選範圍（300m～2km）、類型（餐廳／速食小吃／咖啡廳）與關鍵字篩選
- **午餐轉盤**：從附近店家隨機挑 12 家放上轉盤，轉到哪家吃哪家
- **Google 評價**：每家店都有「⭐ Google 評價」按鈕，會連到 Google 地圖看評分與評論；另有「🚶 導航過去」

## 使用方式
只有一個 `index.html`，不需要 API 金鑰：
- 直接用瀏覽器開啟，或
- 部署到 GitHub Pages（Settings → Pages → 選擇分支）

> 註：「使用我的位置」需在 HTTPS（例如 GitHub Pages）或 localhost 下才能使用。

## 資料來源
- 店家資料：OpenStreetMap（透過 Overpass API）
- 地址搜尋：Nominatim
