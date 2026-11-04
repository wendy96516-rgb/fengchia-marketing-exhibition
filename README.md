# 東協廣場影展專題網頁 - Vibe Coding Prompt 說明與開發紀錄

本專案採用 AI 輔助開發（Vibe Coding），以下為開發過程中使用的核心 Prompt 指令與設計架構摘要：

## 1. 頁面架構與 RWD 布局 Prompt
> "請幫我設計一個 HTML5 / CSS3 網頁，主題為『東協廣場影展專題介紹』。需包含頂部導覽列（Navbar）、側邊欄（Sidebar）以及主要內容區（Main Area）。請使用 CSS Grid System 進行整體版面配置，並透過 Media Queries 實現 RWD 響應式設計，讓手機瀏覽時側邊欄能自動調整為頂部橫向選單。"

## 2. SEO 與組件模組化 Prompt
> "請為此網頁加入完整的 SEO 標籤（Title、Description、Keywords 及 Open Graph 社交圖卡）。此外，請將 CSS 樣式依據全域設定 (style.css)、版面配置 (layout.css) 及組件樣式 (components.css) 進行切分，並建立卡片式元件顯示東協廣場的小吃、超市與服飾亮點。"

## 3. 單頁式分頁切換 (Tab System) Prompt
> "請寫一段輕量化的 JavaScript 語法，實現側邊欄點擊後可在不重新載入頁面的狀況下切換『專題簡介』、『特色亮點』與『標籤翻轉』三個分頁內容。"