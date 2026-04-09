# Databricks 資料處理範例專案

## 專案目的
本專案旨在建立一個簡單但完整的資料處理流程，並實作 Databricks 與 Git 的版本控制整合，作為資料工程與資料平台開發的基礎範例。

## 專案內容
本專案實作基本 ETL（Extract, Transform, Load）流程：

- 讀取原始資料（CSV / DataFrame）
- 資料清理（缺失值處理、格式統一）
- 資料轉換（欄位處理與篩選）
- 輸出處理結果

## 專案結構

project-root/
├─ notebooks/      # Databricks Notebook（主要邏輯）
├─ docs/           # 架構與說明文件
└─ README.md       # 專案說明

- Databricks
- Apache Spark
- Python
- Git / GitHub

## 使用方式
1. 開啟 Databricks workspace
2. 載入本專案 Git folder
3. 執行 notebooks 中的資料處理流程

## 未來規劃
- 導入資料分層架構（Bronze / Silver / Gold）
- 整合 Kafka 作為資料來源
- 建立自動化排程（Databricks Jobs）
- 加入監控與資料品質檢查

## 目標
透過此專案建立：
- Databricks + Git 開發流程
- 基礎資料工程實作能力
- 可擴展的資料處理架構