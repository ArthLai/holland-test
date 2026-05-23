# Holland 職涯六型測評

一個簡易的 Holland Codes (RIASEC) 線上測評工具，60 題、~8 分鐘，輸出使用者的 Top 3 組合與綜合人格描述。

## 特色

- **60 題**：每種人格 10 題，憑直覺作答即可
- **Top 3 組合分析**：不是給單一標籤，而是描述 3 個碼的綜合人格
- **三個維度結果**：
  - 基礎特質性格
  - 職業熱情傾向（含 12 個適合職業推薦）
  - 溝通風格
- **盲點 / 補位建議**：依最弱碼給出實際提醒
- **下載 PNG**：可分享到 IG / LINE
- **複製文字**：可貼回工作坊學習單
- **純單檔 HTML**：無框架、無依賴（除了 html2canvas CDN）

## 使用

直接打開 `index.html`，或部署到任何靜態網站服務。

## 部署到 GitHub Pages

1. 在 repo Settings → Pages
2. Source: `Deploy from a branch`
3. Branch: `main` · `/ (root)`
4. URL: `https://arthlai.github.io/holland-test/`

## 客製化

- **題目**：修改 `index.html` 內 `QUESTIONS` 陣列
- **人格描述**：修改 `CODE_DESC` 物件
- **特殊組合標語**：修改 `SPECIAL_COMBOS`（目前有 30 個組合的客製標語，其餘走通用模板）

## License

MIT
