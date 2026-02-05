# JTI TWP2 生產技術規範參考文檔 (CSU & KPIs)

## 1. 核心專有名詞定義 (Glossary)
* **CSU**: Cold Start Up (冷機啟動)。
* **SWP**: Standard Work Practice (標準作業實務)。
* **OEE**: Overall Equipment Effectiveness (整體設備效率)。
* **NTM**: Non-Tobacco Material (非菸草材料)。
* **Site Owner**: 現場負責人。
    * *註：目前的 CSU SWP Site Owner 為 Onic Liu (Kevin)。*

## 2. CSU 標準作業規範 (Standard Workflow)
根據 TWP2 廠區規範，進行冷機啟動時必須遵循以下邏輯：
1.  **機件核對**：確保所有機台組件、生產模具與 NTM 規格已正確就位。
2.  **空轉測試 (Dry Run)**：正式投入生產前，需進行至少 **5 分鐘** 的空轉測試。
3.  **異常排除**：若在測試階段發現機械異音或數據異常，必須立即回報給 Site Owner。

## 3. KPI 數據分析重點 (Monitoring KPIs)
分析生產逐字稿或報表時，需重點提取以下指標：
* **OEE 表現**：記錄實際效率與目標值的偏差原因。
* **材料損耗**：
    * 非菸草材料損失 (NTM Loss)。
    * 菸草材料損失 (Tobacco Material Loss)。
    * 生產中的菸支損失 (In-process Cigarette Loss)。

## 4. AI 處理指令與格式規範 (AI Processing Rules)
* **翻譯風格**：統一使用「台灣繁體中文商務用語」，嚴禁大陸用語或直譯腔。
* **術語保留**：CSU, SWP, OEE, NTM, SAP, MOM 等術語在任何情況下均不需翻譯。
* **任務清單格式**：所有待辦事項必須轉化為 Microsoft Loop 專用格式：
    * `[ ] 任務內容 - 責任人 - 預計完成日期`
* **知識庫索引**：針對 NotebookLM 的摘要，需包含「關鍵字」與「跨會議追蹤建議」。
