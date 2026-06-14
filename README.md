# SCCC 男士父親節查經聚會 — 活動宣傳頁

**做爸爸，在異鄉**
父親節特備查經聚會 · 2026年6月18日（星期四）晚上 8:00

## 關於此專案

這是 Southampton 中文基督教會（SCCC）為香港 BNO 移民父親而設的活動宣傳頁，
以單一 HTML 檔案（`index.html`）構建，托管於 GitHub Pages。

活動由 Pastor Gavin Li 帶領查經，聚焦於在英國異鄉如何當好一個父親。

## 功能

- 活動資訊展示（日期、時間、地點）
- 針對 BNO 香港移民父親的痛點表達
- 訪客可提前提交討論事情，供講員當晚回應
- WhatsApp、Signal 及複製連結分享功能
- 手機優先設計，兼容桌面瀏覽器

## 技術

- 純 HTML / CSS / JavaScript（單一檔案，無需框架）
- 字型：Noto Serif TC、Noto Sans TC（Google Fonts）
- 資料儲存：訪客討論事情以 `localStorage` 存於本地瀏覽器
- 如需匯出討論事情記錄，在瀏覽器 DevTools Console 執行：`exportQuestions()`

## 部署

1. 將 `index.html` 上傳至此 repo 的 `main` branch
2. 前往 Settings → Pages → Source 選擇 `main` branch，儲存
3. 數分鐘後頁面將於以下網址生效：
   `https://ambrosecheng-bot.github.io/SCCC-men-fathers/`

## 主辦

Southampton 中文基督教會（SCCC）
Ancasta Rd, Southampton, SO14 6SL
[sccc.org.uk](https://sccc.org.uk)
