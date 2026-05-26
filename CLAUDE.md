---
project: circle-game
category: 學科工具集
status: 穩定
version: "子專案文件初始化 2026-05-26"
url: https://wukolo1206.github.io/circle-game/
next_action: 視需要檢查 GitHub Pages 圓規練習與觸控流程
updated: 2026-05-26
---

# CLAUDE.md — circle-game

第六單元「圓」的純 HTML + Canvas 互動工具，包含認識圓、圓規練習、量圓、綜合與地圖題情境。

## 技術框架

- 純 HTML + Canvas + 原生 JavaScript
- 無 build 流程
- GitHub Pages 靜態部署

## 主要頁面

- `index.html`：圓的秘密
- `draw.html`：圓規練習
- `measure.html`：量圓練習
- `combo.html`：綜合練習
- `map.html`：地圖題情境
- `art.html`：延伸視覺活動

## 不能動的地方

- Canvas 繪圖流程與觸控事件，會影響學生平板操作。
- `.bak` 備份檔，除非明確整理版本，不要刪除。

## 部署後驗證清單

- 開啟 `https://wukolo1206.github.io/circle-game/`，確認首頁連結正常。
- 開啟 `draw.html`，確認設定開口、旋轉畫圓與完成提示可用。
- 在手機或平板寬度確認觸控不會拖動畫面或中斷畫圓。
