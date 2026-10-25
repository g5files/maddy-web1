# Maddy_Web1

> 開始日期：2026-10-24　｜　狀態：第二版完成（逐段照原網頁，不自行更改）

**網址**：https://g5files.github.io/maddy-web1/
**GitHub repo**：https://github.com/g5files/maddy-web1 （公開；`reference/` 不上傳）
**更新方式**：改完 `index.html` → 存版本（commit）→ 上傳（push），1～2 分鐘後網址更新

## 目標

把 Canva 網站「G5 Teaching Assistant — Duty Guide 2026-2027」重做成自己的網頁：
https://sgmy2024.my.canva.site/g5-teaching-assistant

這是一份五年級助教（TA）的值班指南：每天的時間表、戶外／室內下課的站崗位置與分工、轉換教室的動線、晚到日與放學值班、保健室通報方式。

做法：內容、章節順序、標題文字完全照原網頁（英文），用單一 HTML 檔重做，雙擊就能開、不用網路。唯一例外是華生指定的午休哨聲（見待確認）。第一版自己加的跳轉列、合併的章節、改寫的字句，第二版都已拿掉或改回。

## 待確認

- [x] 原網站 Lunch Recess 寫「Whistle 8:58」是打錯，2026-10-24 華生確認改成 12:40
- [x] 原網站有兩段 Lunch Recess（餐廳內、操場），華生指定合併成一段（2026-10-24）
- [x] 原網站有兩段 Indoor Lunch Recess，華生指定合併成一段（2026-10-24）
- [x] 每個章節至少一個螢幕高、內容垂直置中，內容多就自動變長，不自動對齊（2026-10-24 華生指定）
- [x] 上方加一排章節按鈕（固定在畫面頂端，13 個章節），點了平滑捲到該章節；章節高度扣掉按鈕列（2026-10-24 華生指定）
- [x] 原網站最上方的照片已放進標題頁當背景（`images/hero.jpg`，從原網站下載，800×533；2026-10-25 華生指定）

## 下一步

- [ ] 華生看過第一版，決定要不要調整內容或樣式

## 重要檔案

| 檔案 | 說明 |
| :-- | :-- |
| `index.html` | 網站本體，雙擊就能開 |
| `images/hero.jpg` | 標題頁背景照片（要跟 index.html 放在一起） |
| `fonts/` | 網站字體 Noto Serif（標題）、Noto Sans（內文），每支手機都用同一種字體；授權見 `fonts/OFL.txt` |
| `reference/canva-text.txt` | 參考網站的全部文字（2026-10-24 抓取） |
| `reference/canva-layout.txt` | 參考網站文字照畫面由上到下的順序（含字級、顏色） |
| `reference/canva-top.png` | 參考網站首頁截圖（手機寬度） |
