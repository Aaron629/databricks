# 資料處理流程架構

## Pipeline 設計

本專案將資料處理分為三個階段：

### 1. Demo ETL
- 建立或讀取原始資料
- 初步處理

### 2. Data Cleaning
- 處理缺失值
- 統一資料格式

### 3. Pipeline
- 整合前兩階段
- 輸出最終結果

---

## 流程圖（概念）

Raw Data → Cleaning → Transformation → Output