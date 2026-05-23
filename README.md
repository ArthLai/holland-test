# Holland 職涯六型測評

一個簡易的 Holland Codes (RIASEC) 線上測評工具，60 題、~8 分鐘，輸出使用者的 Top 3 組合與綜合人格描述。

## 特色

- **36 題**：每種人格 6 題，憑直覺作答 ~5 分鐘完成
- **Top 3 縱覽分析**：不是分碼條列，而是把 3 個碼的特質融成「主軸 + 配色 + 底層」的流動描述，#1 / #2 / #3 的優先序在內容與視覺上都明確
- **三個維度結果**：
  - 基礎特質性格
  - 職業熱情傾向（含 12 個適合職業推薦）
  - 溝通風格
- **盲點 / 補位建議**：依最弱碼給出實際提醒
- **完整 RWD**：手機、平板、桌面各斷點都優化
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
- **三層人格描述**：修改 `LAYERS` 物件（每碼 × 3 段 × 3 層 = 54 條短句）
- **職業列表**：修改 `JOB_LISTS`
- **特殊組合標語**：修改 `SPECIAL_COMBOS`（目前有 33 個組合的客製標語，其餘走通用模板）

## License

MIT
