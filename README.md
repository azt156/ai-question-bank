# AI 題庫分類管家 MVP

這是一個可部署的第一版系統：

- 前端：`index.html`，可放到 GitHub Pages
- 後端：`Code.gs`，放到 Google Apps Script
- AI：Gemini API
- 資料儲存：Google Drive + Google Sheets + Google Docs

## 檔案

- `index.html`：響應式 UI，支援手機、平板、電腦
- `Code.gs`：GAS 後端，負責 AI 分析、Drive 分類、Sheets 索引、Docs 存檔

## 注意

這是 MVP。正式商業化前，建議加入：
- Google OAuth 正式登入流程
- 使用者會員資料庫
- 用量限制
- 付款系統
- 多題拆題
- PDF 多頁處理
- 更完整的知識點分類表
