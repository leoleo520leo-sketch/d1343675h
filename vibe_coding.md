# 🌿 Vibe Coding 實戰手冊與 Prompt 指令集

本專案記錄與整理在進行 **Vibe Coding**（AI 輔助靈感與快速原型開發）時常用的 Prompt 指令、開發流程心法以及實際應用範例。

---

## 📌 什麼是 Vibe Coding？

Vibe Coding 是一種以「意圖與視覺風格為導向」的開發方式。開發者主要專注於**產品主題、視覺氛圍（Vibe）、架構設計與使用者體驗**，並透過清晰的提示詞（Prompts）引導 AI 迅速生成程式碼、樣式與頁面架構。

---

## 🚀 常用 Vibe Coding 提示詞指令

以下整理幾種不同情境下的 Prompt 指令模板：

### 1. 🎨 主題與視覺風格設定 (Style & Theme Vibe)
> **目的：** 快速定義網站的主色調、配色版與設計氛圍。

```text
請幫我將專案的主題調整為 [主題名稱，如：永續房屋/綠色生活]。
視覺風格請採用 [自然/極簡/科技感]，主要配色方案如下：
- 主色（Primary）：[如：森林綠 #244D3C]
- 次色（Secondary）：[如：葉片綠 #4F8062]
- 背景色（Background）：[如：米白色 #F7F5EC]
- 強調色（Accent）：[如：大地棕 #A87955]
請確保整體視覺傳達出 [環保、舒適、自然] 的氛圍。
```

### 2. 🏛️ 單一檔案與整體頁面架構 (Single-File Architecture)
> **目的：** 要求 AI 生成好維護、包含完整結構的單一網頁與組件。

```text
請設計一個包含「導覽列（Navbar）」與「側邊欄（Sidebar）」的完整網頁：
1. 導覽列包含以下項目：[首頁、永續理念、綠色設計、環保建材、生活效益]。
2. 左側邊欄放置快速選單與重點提醒卡片。
3. 採用單一 HTML 檔案架構，整合 CSS (或 Tailwind) 與 JavaScript 互動邏輯。
4. 網頁頁腳（Footer）標註作者名稱：[你的名字/邱奕鈞]。
```

### 3. 🔄 迭代與細節修正 (Refinement & Polishing)
> **目的：** 針對現有版面進行微調與優化。

```text
請基於目前的網頁版型進行以下調整：
- 將原本的標題與內文切換為 [新主題內容]。
- 為導覽列加上 Hover 漸變動畫效果。
- 增加響應式設計（Responsive Design），確保手機端也能正常顯示側邊欄。
```

---

## 💡 Vibe Coding 實踐流程

1. **定義概念（Concept）：** 確定網站核心主題（例如：永續房屋 Sustainable Housing）。
2. **制定基調（Vibe & Tone）：** 挑選搭配的色碼與字體風格。
3. **結構下達（Prompting）：** 使用結構化的提示詞向 AI 描述 layout 與功能需求。
4. **快速預覽與微調（Iterate）：** 檢視生成的成果，針對細節進行提問與修正。

---

## 🔗 GitHub 專案連結指南

你可以將本 Markdown 檔案命名為 `README.md` 上傳至 GitHub 專案儲存庫中。

1. **建立 GitHub Repository：**
   - Repository Name: `vibe-coding-guide`
2. **將 `README.md` 推送至 GitHub：**
   ```bash
   git init
   git add README.md
   git commit -m "docs: add vibe coding instruction guide"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/vibe-coding-guide.git
   git push -u origin main
   ```
3. **專案連結展示範例：**
   - 🔗 **GitHub Repository:** `https://github.com/YOUR_USERNAME/vibe-coding-guide`
   - 📄 **文件檢視：** `https://github.com/YOUR_USERNAME/vibe-coding-guide/blob/main/README.md`

---

*作者：邱奕鈞 | 專注於永續設計與 AI 輔助網頁開發*