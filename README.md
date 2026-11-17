# Maze Studio｜平面設計接案作品集

Maze Studio 的個人品牌 Landing Page，展示品牌識別、型錄與包裝設計作品——「把複雜的專業，變成好懂的視覺。」

## 網站功能

- **固定導覽列（Sticky Nav）**：捲動時維持在頂部，並帶有毛玻璃效果，點擊連結可平滑捲動至各區塊。
- **Hero 主視覺**：品牌標語與進場淡入動畫。
- **精選作品**：展示三個案例——鋼構精工品牌重塑、自動化設備雙語型錄、山嵐咖啡包裝系列。
- **聯絡區塊**：引導訪客洽詢專案合作。
- **RWD 響應式設計**：針對平板（≤ 920px）與手機（≤ 640px）調整版面，觸控目標至少 44px，並避免橫向捲動。
- **無障礙考量**：支援 `prefers-reduced-motion`，偏好減少動態的使用者會關閉動畫。

## 使用技術

- **HTML5**：語意化標籤（`nav`、`section`、`footer`），語系設定為 `zh-Hant`。
- **CSS3**：CSS 變數（設計 token）、Flexbox / Grid 版面、漸層背景、`backdrop-filter`、Media Queries。
- **Google Fonts**：Inter、Noto Sans TC、Noto Serif TC。
- 少量原生 JavaScript 處理進場動畫，無任何框架或建置工具。

## 如何用瀏覽器開啟

不需安裝任何套件，直接開啟 `index.html` 即可：

1. **直接雙擊**：在 Finder / 檔案總管中雙擊 `index.html`，系統會以預設瀏覽器開啟。
2. **拖曳開啟**：把 `index.html` 拖進 Chrome、Safari、Edge 或 Firefox 視窗。
3. **使用終端機（macOS）**：

   ```bash
   open index.html
   ```

> 提示：想檢查手機版效果，可在瀏覽器按 `F12`（macOS 為 `Cmd + Option + I`）開啟開發者工具，切換到裝置模擬模式。

## 專案結構

```
claude-lab/
├── index.html   # Landing Page（HTML + CSS 皆在此檔）
├── note.txt     # 筆記
└── README.md    # 專案說明
```
