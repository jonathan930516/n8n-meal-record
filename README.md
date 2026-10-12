# n8n Meal Record Automation

## 專案介紹
使用 n8n 建立三餐紀錄自動化系統，整合表單、n8n Data Table 與 Google Sheets，方便記錄及管理每日飲食資訊。

## 主要功能
- 透過表單輸入每日三餐資料
- 自動儲存飲食紀錄
- 整合 Google Sheets
- 記錄日期、餐別、食物、價格及飲料
- 記錄甜度、冰量、地點與備註
- 支援資料整理及後續分析

## 使用技術
- n8n：自動化工作流程
- Google Sheets：資料儲存與整理
- n8n Data Table：結構化資料管理
- JSON：工作流程設定檔
- GitHub：版本控制與專案備份

## 工作流程
1. 使用者填寫三餐紀錄表單
2. n8n 接收表單資料
3. 將資料存入 n8n Data Table
4. 將資料同步新增至 Google Sheets
5. 完成飲食紀錄

## 專案檔案
- `三餐紀錄.json`：n8n 工作流程匯出檔

## 注意事項
匯入工作流程後，需要自行設定 Google Sheets 憑證及相關資料表。
