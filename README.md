# 個人履歷網站（Jekyll Minimal Resume 改良版）

## 專案簡介
本專案為個人履歷網站，基於 Jekyll 與 murraco/jekyll-theme-minimal-resume 主題進行深度客製化，適合學術、工程、研究等領域的個人簡歷展示。內容涵蓋學經歷、專案、技能、活動、語言能力等，並支援多媒體與現代化互動設計。

## 主要檔案用途
- `index.html`：網站首頁，依序引入各區塊（關於我、技能、專案、學歷、活動、語言、聯絡）。
- `_config.yml`：Jekyll 站台設定（標題、描述、導覽、社群連結等）。
- `_data/`：YAML 格式資料（personal.yml：個人簡介、skills.yml：技能、projects.yml：專案）。
- `_includes/`：各區塊 HTML 模組（about、skills、projects、education、activities、languages、contact、nav、footer 等）。
- `_layouts/default.html`：網站主版型，負責全站結構與樣式引入。
- `assets/`：靜態資源（css 樣式、圖片、字型、js 腳本）。
- `src/`：SCSS 原始碼、JS 原始碼、字型來源。
- `gulpfile.js`：前端自動化工具設定（SCSS 編譯、JS 合併壓縮、圖片優化等）。
- `Gemfile`：Jekyll 及相關 Ruby 套件安裝設定。

## 技術棧
- Jekyll（靜態網站產生器）
- HTML5 / CSS3 / SCSS（含 SASS 預處理器）
- JavaScript（含 particles.js、sweet-scroll）
- Gulp（前端自動化流程）
- Font Awesome、Devicon（圖示字型）
- YAML（資料結構）

## 製作流程與客製化重點
1. 以 [murraco/jekyll-theme-minimal-resume](https://github.com/murraco/jekyll-theme-minimal-resume) 為基礎 fork 並本地開發。
2. 重新設計導覽列、區塊結構，將內容模組化（_includes/）並支援 YAML 資料驅動。
3. 全面中文化，並針對台灣學術/工程背景調整內容分類與呈現方式。
4. 增加多媒體展示（圖片、PDF 下載、GitHub 連結等），支援自訂技能、專案、活動等區塊。
5. 樣式與配色優化，強化 RWD 響應式設計，並調整字型、間距、色彩以提升閱讀體驗。
6. 前端自動化流程（Gulp）優化，支援 SCSS 編譯、JS 壓縮、圖片優化等。
7. 移除原主題的英文假資料與贊助連結，改為個人化內容。
8. 增加本地化設定與部署說明，方便 GitHub Pages 快速上線。

### 與原主題的主要差異
- 全面中文化，並針對台灣學術/工程背景優化內容結構。
- 導覽列、各區塊、資料來源（YAML）皆重新設計，支援高度自訂。
- 增加多媒體（圖片、PDF、GitHub 連結）與現代化互動效果。
- 樣式、配色、字型、RWD 響應式設計皆大幅優化。
- 前端自動化流程（Gulp）與 SCSS 架構更完善。
- 移除原主題的英文假資料與贊助連結，改為個人化內容。

---

