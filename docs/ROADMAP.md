# ROADMAP

## 專案方向

本專案目前已具備完整的 iPAS AI 應用規劃師初級學習網站內容，但內容組織仍處於「補強區塊先長出來、課綱章節後補上」的狀態。

下一階段的核心方向不是新增功能，而是整理現有學習內容，讓網站從「考點資料庫」逐步變成「依七章課綱學習的教材」。

## 目前階段

### 第一階段：整理現有學習內容

狀態：文件分析完成，尚未實作網站重整。

本階段目標：

- 盤點 `index.html` 所有章節
- 建立章節內容對照表
- 找出補強內容尚未回歸原章節的項目
- 提出重整方案
- 不修改網站功能
- 不修改 UI
- 不修改題庫內容
- 不實作程式

本次已完成：

- `docs/HANDOFF.md` 更新章節盤點與交接資訊
- `docs/ROADMAP.md` 更新重整路線

## 章節重整目標

最終內容架構建議以七章課綱為主體：

1. L111 人工智慧基礎概論
2. L112 資料處理與分析概念
3. L113 機器學習概念
4. L114 鑑別式 AI 與生成式 AI
5. L121 No Code / Low Code 概念
6. L122 生成式 AI 應用領域與工具使用
7. L123 生成式 AI 導入評估規劃

每章建議固定包含：

- 章節導讀
- 考試在考什麼
- 必背名詞
- 易混淆比較
- 官方題型
- 實務案例
- 常見陷阱
- 情境練習

## 建議實作順序

### Step 1：L112 試點重整

狀態：待確認後執行。

任務範圍：

- 僅整理既有內容
- 不新增考點
- 不修改題庫內容
- 不修改 UI
- 不修改 JS 功能

L112 應回收內容：

- 資料整合
- 資料清理
- Data Leakage
- 結構化資料
- 非結構化資料
- 半結構化資料
- 正規化
- 標準化
- One-hot Encoding
- Label Encoding
- SMOTE
- Data Privacy / Data Security / Data Governance
- Access Control
- Least Privilege
- Data Integrity
- 對應官方題型：Data Leakage、SMOTE、One-hot Encoding
- 對應陷阱：先標準化再分割、SMOTE 刪除多數樣本
- 對應情境題：1、2、7、8、14

完成標準：

- L112 章內可獨立完成「名詞理解 → 題型辨識 → 陷阱補強 → 情境練習」
- 原本散落在補強區的 L112 內容有清楚歸屬
- 不破壞現有導覽與進度功能

### Step 2：L113 重整

狀態：待 L112 試點完成後執行。

L113 應回收內容：

- 監督式學習
- 非監督式學習
- 強化學習
- 半監督式學習
- 分類
- 回歸
- 分群
- 訓練資料
- 測試資料
- 過擬合
- 欠擬合
- CNN
- RNN / LSTM
- KNN
- 決策樹
- SVM
- Softmax
- Wide and Deep
- Precision / Recall
- Data Drift / Concept Drift

### Step 3：L122 重整

狀態：待 L112、L113 完成後執行。

L122 應回收內容：

- LLM
- Token
- Context Window
- Temperature
- Chat History
- Prompt Engineering
- Zero-shot
- One-shot
- Few-shot
- Chain of Thought
- RAG
- Fine-tuning
- PEFT
- LoRA
- Knowledge Distillation
- AI 工具分工案例

### Step 4：L123 重整

狀態：待 L122 完成後執行。

L123 應回收內容：

- ROI
- TCO
- 可行性評估
- 分階段導入
- MVP
- Data Governance
- Vendor Lock-in
- Prompt Injection
- Prompt Leakage
- Hallucination
- 資料完整性
- 生成式 AI 風險管理
- 導入成本與治理陷阱

### Step 5：L111、L114、L121 補齊

狀態：待主要高頻章節完成後執行。

L111 應補齊：

- AI 倫理五大核心原則
- AI 基本法 / 金融揭露義務
- XAI 技術
- 偏見、公平性、透明性、可解釋性、問責性

L114 應補齊：

- Generative AI vs Discriminative AI
- VAE
- GAN
- Transformer
- 生成模型與鑑別模型邊界

L121 應補齊：

- API
- Webhook
- Dify 元件
- Branch / Router
- Iterator
- Formatter
- Array Aggregator
- No-Code / Low-Code 的維護、安全與平台鎖定限制

## 保留獨立區塊

即使內容回歸七章，以下區塊建議保留為總複習或索引：

- 考試資訊
- 學習進度
- 考前 30 分鐘速讀
- 易混淆名詞比較總索引
- 官方題庫對應總覽
- 考試陷阱總索引
- 混合情境練習

這些區塊的定位應改為「複習入口」，不是主要內容儲存地。

## 不做事項

目前不建議做：

- 新增功能
- 改 UI
- 改色彩與版面
- 改 checkbox / localStorage 進度功能
- 新增測驗計分系統
- 新增後端
- 改寫題庫內容
- 新增外部套件
- 將單頁網站拆成框架專案

## 下一個最適合任務

下一個最適合任務：

「請依照 ROADMAP Step 1，只重整 L112 章節內容，把既有 L112 相關補強內容搬回 L112，不新增新功能、不改 UI、不改題庫文字。」

建議執行方式：

1. 先複查 L112 相關內容在 `index.html` 的位置。
2. 設計 L112 章內固定順序。
3. 搬移既有內容，不改寫考點。
4. 保留原本補強區作為索引，或等待使用者確認後再精簡重複內容。
5. 驗證頁面錨點、學習進度、展開區塊與 scroll top 功能未受影響。

## 完成標準

第一輪網站重整完成時，應達到：

- 使用者可以依七章課綱逐章學習
- 每章都有名詞、比較、題型、陷阱、案例與練習
- 補強內容不再只集中在前半段
- 重複內容減少，但考點不遺失
- 功能、UI、題庫文字維持穩定
