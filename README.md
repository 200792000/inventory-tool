# 盤點行程異動聯絡單產生器 — 前端

## 部署到 GitHub Pages

1. 建立 GitHub Repository（例：inventory-tool）
2. 上傳 index.html 到根目錄
3. Settings → Pages → Source 選 main → Save
4. 取得網址（https://你的帳號.github.io/inventory-tool）

## 設定 API 網址

部署後端到 Render 後，取得 API 網址，修改 index.html 第一行：

```javascript
var API_URL = 'https://你的API網址.onrender.com';
```

## 使用流程

1. 開啟網頁
2. 上傳版本一（原始班表）
3. 上傳版本二（異動後班表）
4. 自動比對，顯示差異
5. 點擊下載，取得完整格式聯絡單
