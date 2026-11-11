# 🎬 舊驛新憶｜大二影展專題網頁專案

> **專題主題**：透過鏡頭與網頁設計，探索臺中舊火車站（臺中驛）及其周邊鐵道文化園區的歷史記憶與現代重生。
> **學號 / 作者**：D1420515 影展專題製作小組

---

## 🌐 專案線上預覽與展示
* **GitHub Pages 成果展示網址**：[https://你的帳號名稱.github.io/你的倉庫名稱/](https://your-github-username.github.io/your-repo-name/)
* **線上圖床與資源主機**：[專案圖床位置](https://chuchinn.10001mb.com/)

---

## 🛠️ 專案技術規格與亮點 (Features)

本專案完全依照網頁開發規範與期末專題要求打造，具備以下核心技術：

1. **語意化 HTML5 架構**：
   * 運用 `<header>`、`<nav>`、`<aside>`、`<main>`、`<article>`、`<section>` 等語意化標籤，結構清晰且利於維護。
2. **完整 SEO 最佳化規劃**：
   * 內含 `<title>`、Meta Description、作者標籤與機器人爬蟲設定。
   * 完整設置 **Open Graph (OG)** 社群分享標籤（支援 Facebook、Line 等通訊軟體預覽圖與標題呈現）。
3. **現代 Grid System 搭配 Flexbox 佈局**：
   * 採用 **CSS Grid** 建立左側固定導覽列與右側主要內容的雙欄 Layout。
   * 內部區塊搭配 **Flexbox** 進行彈性對齊與網格排列。
4. **完整 RWD 響應式設計 (Responsive Web Design)**：
   * 透過 `@media screen and (max-width: ...)` 斷點設定，在桌機、平板與手持行動裝置上皆能完整顯示所有排版與資訊。
5. **模組化 CSS 檔案結構**：
   * 將樣式獨立切割並分類至 `css/` 檔案匣內，方便專案管理與交作業審查。
6. **豐富多媒體互動**：
   * 整合 YouTube 預告片與正片嵌入播放器。
   * 嵌入自適應 Google 官方地圖 (`<iframe>`)，標註臺中驛鐵道文化園區精準地理位置。

---

## 📁 專案檔案結構 (Project Directory)

本專案目錄結構如下，樣式與圖片皆進行了模組化分類管理：

```text
festival-project/
├── index.html              # 主 HTML 網頁檔案（含完整 SEO 與內容結構）
├── README.md               # 專題說明與 GitHub 介紹文件
├── css/
│   ├── style.css           # 核心結構、Grid/Flexbox 排版與視覺樣式表
│   └── responsive.css      # RWD 響應式手持裝置斷點微調樣式表
└── images/
    ├── hero-banner.jpg     # 頁首主視覺海報 / 舊車廂劇照
    └── poster.jpg          # 專題官方直式海報
