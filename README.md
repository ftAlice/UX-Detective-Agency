# UX Detective Agency

> 一個以黑色偵探美學為核心的互動式網頁展示專案。

---

## 專案簡介

**UX Detective Agency** 是一個以監控、偵查為視覺主題的暗色調互動式網頁組件。
專案以純 HTML、CSS 與 JavaScript 實作，無需任何框架或外部依賴，
旨在呈現高品質的沉浸式使用者體驗設計——讓每一位訪客從進入頁面的那一刻起，
便能感受到一雙無聲注視著他們的眼睛。

---

## 主要功能

### 🎥 互動式 CCTV 鏡頭組件
- 壁掛式監視攝影機 3D 渲染，含玻璃鏡頭、金屬機身、螺栓細節與指示燈
- 鏡頭玻璃反光隨游標位置即時偏移，強化真實感

### 👁 全域游標追蹤
- 鏡頭持續跟蹤使用者游標，無論游標移動至畫面任何位置
- 動作具有機械延遲感——慣性跟隨而非即時反應，模擬真實攝影機重量感

### ⚡ 隨機訊號干擾效果
- 不定時觸發畫面閃爍與機身位移，模擬類比訊號不穩
- 鏡頭虹膜偶有突發微幅位移，模擬機械重新對焦

### 🖥 HUD 監控介面
- 即時顯示系統時間、攝影機編號（`CAM-01`）、錄影狀態
- 動態顯示游標座標（`X` / `Y`）

### 🎬 Hover 互動（焦點狀態）
- 游標懸停鏡頭時觸發「系統喚醒」效果
- 紅色光暈脈衝展開，顯示 `TARGET ACQUIRED` 警示文字
- 自訂游標同步放大，強化目標鎖定的視覺回饋

### 🎞 環境質感
- 全頁膠片顆粒（Film Grain）疊加，模擬老舊監控畫面
- 掃描線（Scanlines）持續滾動，強化類比視覺風格
- 邊緣暗角（Vignette）讓場景聚焦感更強
- 四角 HUD 標記框，呼應監控系統介面設計語言

---

## 技術棧

| 項目 | 內容 |
|------|------|
| 語言 | HTML5 / CSS3 / Vanilla JavaScript |
| 字型 | Google Fonts（Share Tech Mono、Rajdhani） |
| 動畫 | CSS Keyframes + `requestAnimationFrame` |
| 外部依賴 | 無 |

---

## 如何運行

本專案為純靜態網頁，**無需安裝任何工具或套件**。

### 方法一：直接開啟（最簡單）

在 Finder 中找到 `index.html`，雙擊即可在預設瀏覽器開啟。

### 方法二：使用 VS Code Live Server

1. 以 VS Code 開啟專案資料夾
2. 安裝 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 擴充功能
3. 在 `index.html` 上按右鍵 → **Open with Live Server**

### 方法三：使用本機 HTTP 伺服器

```bash
# Python 3
python3 -m http.server 8080

# 開啟瀏覽器後訪問
http://localhost:8080/index.html
```

> **建議瀏覽器**：Chrome 或 Firefox 最新版本，以獲得最佳動畫效能與視覺效果。

---

## 專案結構

```
UX Detective Agency/
├── index.html       # 主組件頁面（含全部 CSS 與 JS）
├── images/         # 圖片資源目錄（保留供未來擴充）
├── .gitignore      # Git 忽略清單
└── README.md       # 專案說明文件
```

---

## 授權

本專案為個人作品集展示用途，保留所有權利。
