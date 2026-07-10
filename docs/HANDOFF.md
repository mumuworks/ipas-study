# HANDOFF

## 2026-07-10｜L113～L123 第一階段內容重整一次完成

本次任務依照 L112 的整理方式，完成 `L113`、`L114`、`L121`、`L122`、`L123` 的既有內容回收整理。已修改 `index.html` 內容順序，但未修改 CSS、UI、JavaScript、題目文字，未 commit、未 push。

已完成：

- 將 L113 尚留在補強區的快答與陷阱解析補回 `L113 機器學習概念`。
- 將 L114 相關「必背名詞、易混淆比較、補充內容」搬回 `L114 鑑別式 AI 與生成式 AI`。
- 將 L121 相關「必背名詞、易混淆比較、官方題型、補充內容」搬回 `L121 No Code / Low Code 概念`。
- 將 L122 相關「必背名詞、易混淆比較、官方題型、實務案例、補充內容」搬回 `L122 生成式 AI 應用領域與工具使用`。
- 將 L123 相關「必背名詞、易混淆比較、官方題型、實務案例、補充內容」搬回 `L123 生成式 AI 導入評估規劃`。
- 從原本散落位置移除已搬移的重複教學卡片。
- 移除搬空後的「科目二｜生成式 AI 應用與規劃 — 高頻考點」空摺疊區。
- 保留原有樣式 class 與 HTML 結構，不新增 CSS。
- 保留原有 JavaScript 與 `localStorage` 進度功能。

本次整合進 L113 的新增回收內容：

- 監督式 vs 非監督式快答補充
- Data Drift vs Concept Drift 快答補充
- 非監督式學習陷阱解析

本次整合進 L114 的內容：

- 生成對抗網路（GAN）
- Generative AI vs Discriminative AI
- VAE 的分類陷阱解析

本次整合進 L121 的內容：

- No Code
- Low Code
- API
- Webhook
- Branch / Router
- Iterator
- Formatter
- Array Aggregator
- API vs Webhook
- No Code vs Low Code
- 題型07｜Webhook
- API / Webhook 高頻補充
- Dify 平台元件
- No-Code / Low-Code 安全與維護陷阱解析

本次整合進 L122 的內容：

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
- RAG vs Fine-tuning
- Prompt Engineering vs Fine-tuning
- Token vs Context Window
- LoRA vs Knowledge Distillation
- 題型05｜RAG
- 題型06｜Token
- 題型10｜LoRA / PEFT
- 案例③｜AI 協作流程
- LLM / Prompt / 企業知識應用 / Chat History 高頻補充
- RAG vs Fine-tuning 快答
- Few-shot Prompting vs Fine-tuning 快答
- Chat History、RAG、Few-shot、Temperature、CoT 相關陷阱解析

本次整合進 L123 的內容：

- Hallucination
- Vendor Lock-in
- ROI
- TCO
- Feasibility Assessment
- Phased Implementation
- MVP
- Prompt Injection vs Prompt Leakage vs Hallucination
- 題型08｜Vendor Lock-in
- 題型09｜AI Governance
- 案例②｜行政管理平台 / MAP
- Vendor Lock-in 高頻補充
- ROI / TCO 成本效益分析
- Data Governance 高頻補充
- Prompt Injection 高頻補充
- Prompt Injection vs Prompt Leakage vs Hallucination 快答
- TCO 陷阱解析

本次保留原位置：

- `AI 治理`、偏見、公平性、透明性、可解釋性、問責性、Human-in-the-loop 等名詞卡，因內容明確屬 L111 範圍，本輪範圍未包含 L111。
- `SHAP vs LIME vs Saliency Map` 與相關快答，因內容明確屬 L111 XAI / AI 治理範圍。
- `AI 倫理與法規` 高頻補充，因內容明確屬 L111。
- 考點星級彙整表，作為總複習索引保留。
- 考前 30 分鐘速讀，作為總複習索引保留。
- 第二階段情境對照練習，因本次要求未包含情境題搬移，且前次 L112/L113 試點也未搬移情境題。

發現的重複或跨章內容：

- `VAE` 目前名詞仍在 L113 模型補強，VAE 分類陷阱解析已回 L114 生成模型脈絡；若要完全單一歸屬，需人工決定 VAE 最終放 L113 或 L114。
- `Data Governance` 同時出現在 L112 的資料治理名詞與 L123 的企業導入治理補充；一者偏資料管理，一者偏導入治理，建議後續人工確認是否保留跨章。
- `RAG` 同時出現在 L122 工具使用與 L123 風險管理原章關鍵字；一者偏工具原理，一者偏降低幻覺風險，建議保留或人工決定是否只留 L122。

待人工確認：

- 是否下一輪納入 `L111`，將 AI 治理、倫理、XAI、金融 AI 揭露義務等內容完整回收至 L111。
- 是否要把第二階段情境題也拆回各章，或繼續保留為總複習練習區。
- 是否要把「官方題庫對應」「實務案例對照」這些原總覽區改成純索引說明，避免章內搬移後看起來偏空。

本次驗證：

- 已執行 `git diff --check`，結果通過。
- 已檢查 diff，未出現 CSS 或 JavaScript 變更。

下一個最適合任務：

「人工確認跨章歸屬與是否納入 L111，確認後再做第二輪：清理總覽區空殼與建立索引式導覽文字。」

## 2026-07-10｜L113 第一階段內容重整

本次任務只處理 `L113 機器學習概念`，沿用上一輪 L112 的整理方式，已修改 `index.html` 內容順序，但未修改 CSS、UI、JavaScript、題目文字，未 commit、未 push。

已完成：

- 將 L113 相關「必背名詞」搬回 `L113 機器學習概念` 章節內。
- 將 L113 相關「易混淆比較」搬回 L113 章節內。
- 將 L113 相關「官方題型」搬回 L113 章節內。
- 將 L113 相關「補充內容」搬回 L113 章節內。
- 從原本散落位置移除已搬移的重複內容。
- 保留原有樣式 class 與 HTML 結構，不新增 CSS。
- 保留原有 JavaScript 與 `localStorage` 進度功能。

本次整合進 L113 的內容：

- 監督式學習
- 非監督式學習
- 強化學習
- 分類
- 回歸
- 分群
- 訓練資料
- 測試資料
- 模型
- 過擬合
- 欠擬合
- CNN
- RNN
- Transformer
- VAE
- Softmax
- KNN
- 決策樹
- SVM
- Wide and Deep
- Supervised vs Unsupervised Learning
- Classification vs Regression vs Clustering
- Overfitting vs Underfitting
- Data Drift vs Concept Drift
- CNN vs LSTM vs Transformer
- Precision vs Recall
- 題型04｜Unsupervised Learning
- 三種學習類型比較
- 半監督式學習
- LSTM

本次未處理：

- L111、L114、L121、L122、L123 的內容重整
- 考試陷阱專區
- 情境對照練習
- 星級彙整表的關鍵字總覽
- 題庫文字調整
- UI 或功能調整

注意事項：

- 名詞庫原本的「機器學習」小節已因內容回歸 L113 而移除。
- 高頻考點庫中的「機器學習類型」與「模型架構」補充段已回歸 L113。
- 星級彙整表仍保留 L113 相關關鍵字，作為總複習索引，不視為重複教學卡片。
- `Training Data vs Test Data` 比較仍保留在 L112，因它在 L112 的 Data Leakage脈絡中使用；L113 則補回「訓練資料 / 測試資料」完整名詞卡。

下一個最適合任務：

「確認 L113 重整後閱讀順序，再依同樣模式整理 L114 鑑別式 AI 與生成式 AI。」

## 2026-07-10｜L112 第一階段內容重整

本次任務只處理 `L112 資料處理與分析概念`，已修改 `index.html` 內容順序，但未修改 CSS、UI、JS 功能、題庫文字，未 commit、未 push。

已完成：

- 將 L112 相關「必背名詞」搬回 `L112 資料處理與分析概念` 章節內。
- 將 L112 相關「易混淆比較」搬回 L112 章節內。
- 將 L112 相關「官方題型」搬回 L112 章節內。
- 將 L112 相關「灶囍訂購系統」實務案例搬回 L112 章節內。
- 從原本散落位置移除已搬移的重複內容。
- 保留原有樣式 class 與 HTML 結構，不新增 CSS。
- 保留原有 JavaScript 與 `localStorage` 進度功能。

本次整合進 L112 的內容：

- 資料整合
- 資料清理
- 資料洩漏
- 結構化資料
- 非結構化資料
- 半結構化資料
- 正規化
- 標準化
- One-hot Encoding
- Label Encoding
- SMOTE
- 隱私
- 安全性
- 資料治理
- 存取控制
- 最小權限原則
- 資料完整性
- One-hot Encoding vs Label Encoding
- Normalization vs Standardization
- Training Data vs Test Data
- Data Privacy vs Data Security vs Data Governance
- Access Control vs Least Privilege
- 題型01｜Data Leakage
- 題型02｜SMOTE
- 題型03｜One-hot Encoding
- 案例①｜灶囍訂購系統

本次未處理：

- L111、L113、L114、L121、L122、L123 的內容重整
- 考試陷阱專區
- 情境對照練習
- 高頻考點庫
- 題庫文字調整
- UI 或功能調整

注意事項：

- 名詞庫原本的「資料處理」小節已因內容回歸 L112 而移除空標題。
- 易混淆比較、官方題型、實務案例總覽區會因 L112 內容移出而少部分卡片；這符合「搬移回原章節」方向。
- 高頻考點庫中仍保留原本的高頻整理內容，本次未移動，避免超出使用者指定的「名詞、易混淆比較、官方題型、實務案例」範圍。

下一個最適合任務：

「檢查 L112 重整後的閱讀順序與錨點體驗，確認後再用同樣方式整理 L113 機器學習概念。」

## 2026-07-10｜前次內容盤點紀錄

日期：2026-07-10

此段為前次第一階段內容盤點紀錄；當時只更新文件，尚未修改 `index.html`。

已完成：

- 閱讀 `docs/PROJECT_CHARTER.md`
- 閱讀 `docs/HANDOFF.md`
- 閱讀 `docs/ROADMAP.md`
- 盤點 repository 內容
- 分析 `index.html` 目前所有章節與補強區塊
- 建立章節內容對照
- 找出補強內容尚未回歸原課綱章節的項目
- 提出下一階段章節重整方向

目前三份 docs 在本次開始前皆為空檔；核心內容集中於 `index.html`。

## Repository 現況

目前檔案：

- `README.md`：空檔
- `index.html`：主要網站，3134 行，包含所有內容、樣式與互動
- `docs/PROJECT_CHARTER.md`：空檔
- `docs/HANDOFF.md`：已更新
- `docs/ROADMAP.md`：已更新
- `docs/CHANGELOG.md`：已建立

## 目前章節清單

`index.html` 目前依頁面順序包含以下主要區塊：

1. 頁首
   - 標題：iPAS AI 應用規劃師初級考試學習網站
   - 教材版本 v3
   - 學習策略：名詞理解 → 官方題庫 → 錯題補強

2. 考試資訊
   - 考試日期：11 月 7 日
   - 目前策略
   - 適合對象

3. 快速導覽
   - 考試資訊
   - 學習進度
   - 必背名詞庫
   - 易混淆比較
   - 官方題庫對應
   - 實務案例
   - 高頻考點庫
   - 考前 30 分鐘
   - 課綱詳讀
   - 考試陷阱
   - 情境練習

4. 學習進度
   - 對應七章課綱
   - 使用 checkbox 與 `localStorage` 記錄進度

5. 必背專有名詞庫
   - 科目一：人工智慧基礎概論
   - 科目二：生成式 AI 應用與規劃
   - 以「白話、常考法、錯誤選項、實務」整理大量名詞

6. 易混淆名詞比較
   - 20 組主要比較
   - 包含基礎混淆與進階混淆

7. 官方題庫對應
   - 10 個官方題型對應

8. 實務案例對照
   - 灶囍訂購系統
   - 行政管理平台 / MAP
   - AI 協作流程

9. 高頻考點庫
   - 科目一高頻考點
   - 科目二高頻考點
   - 考點星級彙整表
   - 容易混淆觀念快答

10. 考前 30 分鐘速讀
    - 必背 10 個
    - 易混淆 10 組
    - 官方題庫最常見陷阱 10 個

11. 附錄｜課綱七章詳讀
    - L111 人工智慧基礎概論
    - L112 資料處理與分析概念
    - L113 機器學習概念
    - L114 鑑別式 AI 與生成式 AI
    - L121 No Code / Low Code 概念
    - L122 生成式 AI 應用領域與工具使用
    - L123 生成式 AI 導入評估規劃

12. 考試陷阱專區
    - 12 題陷阱解析

13. 第二階段｜情境對照練習
    - 20 題自編情境題

14. 頁尾
    - 版本與來源說明

## 章節內容對照表

| 目前區塊 | 主要內容 | 對應課綱章節 | 備註 |
| --- | --- | --- | --- |
| 考試資訊 | 日期、策略、適合對象 | 全站導讀 | 保留在最前面即可 |
| 學習進度 | 七章 checkbox | L111-L123 | 功能不動 |
| 必背名詞庫：資料處理 | 資料整合、清理、洩漏、資料型態、正規化、標準化、編碼、SMOTE | L112 | 多數內容應回到 L112 詳讀章 |
| 必背名詞庫：機器學習 | 監督式、非監督式、強化式、分類、回歸、分群、訓練/測試、過擬合/欠擬合 | L113 | 多數內容應回到 L113 詳讀章 |
| 必背名詞庫：模型與 AI 技術 | CNN、RNN、Transformer、VAE、GAN、Softmax、KNN、決策樹、SVM、Wide and Deep | L113、L114 | 模型基礎回 L113；生成模型與生成/鑑別差異可回 L114 |
| 必背名詞庫：AI 治理 | 治理、偏見、公平性、透明性、可解釋性、問責性、隱私、安全、人機協作 | L111、L112、L123 | 治理/倫理回 L111；資料隱私安全回 L112；導入風險回 L123 |
| 必背名詞庫：LLM 基礎 | LLM、Token、Context Window、Temperature、Hallucination、Chat History | L122、L123 | 工具與使用回 L122；風險如幻覺回 L123 |
| 必背名詞庫：Prompt | Prompt Engineering、Zero/One/Few-shot、CoT | L122 | 應回 L122 |
| 必背名詞庫：企業知識應用 | RAG、Fine-tuning、PEFT、LoRA、Knowledge Distillation | L122、L123 | 工具/技術回 L122；導入選型與成本回 L123 |
| 必背名詞庫：No Code / Low Code | No Code、Low Code、API、Webhook、Branch、Iterator、Formatter、Aggregator、Vendor Lock-in | L121、L123 | 平台元件回 L121；供應商鎖定回 L123 |
| 必背名詞庫：導入與管理 | ROI、TCO、可行性、分階段、MVP、資料治理、存取控制、最小權限、資料完整性 | L123、L112 | 成本效益與導入回 L123；資料權限與完整性回 L112 |
| 易混淆名詞比較 | 20 組比較 | L112-L123 | 目前集中成獨立補強區，可拆回各章的「易混淆」小節 |
| 官方題庫對應 | 10 題型 | L112-L123 | 可保留總覽，也可在各章加入對應題型 |
| 實務案例對照 | 灶囍、MAP、AI 協作 | L111-L123 | 適合保留總覽，並在各章補充章內案例 |
| 高頻考點庫 | 科一/科二高頻與星級 | L111-L123 | 目前重複大量名詞庫內容，適合轉為各章「高頻補強」 |
| 考前 30 分鐘 | 壓縮複習清單 | 全章 | 可保留獨立速讀區 |
| 附錄七章詳讀 | 依 L111-L123 逐章說明 | L111-L123 | 建議升格為主內容骨架 |
| 考試陷阱專區 | 12 題陷阱 | L112-L123 | 建議拆回各章，或保留索引並連回原章 |
| 情境對照練習 | 20 題自編題 | L111-L123 | 建議依題目考點回歸各章練習 |

## 每章目前包含哪些內容

### L111 人工智慧基礎概論

目前附錄章節包含：

- AI 的定義與分類
- 強 AI / 弱 AI
- AI 與機器學習 / 深度學習關係
- AI 治理概念
- AI 倫理、責任歸屬、透明度、公平性、法規與治理框架

散落在補強區的相關內容：

- AI 治理
- 偏見
- 公平性
- 透明性
- 可解釋性
- 問責性
- Human-in-the-loop
- AI 基本法 / 金融機構運用 AI 規範
- AI 倫理五大核心原則
- XAI：SHAP、LIME、Saliency Map
- 情境題 17、18、19

### L112 資料處理與分析概念

目前附錄章節包含：

- 資料基本概念與來源
- 結構化資料 / 非結構化資料
- 資料整理與分析流程
- 資料清理
- 資料隱私與安全
- 存取控制
- 個人資料

散落在補強區的相關內容：

- 資料整合
- 資料清理
- 資料洩漏
- 結構化 / 非結構化 / 半結構化資料
- 正規化 / 標準化
- One-hot Encoding / Label Encoding
- SMOTE
- Data Privacy / Data Security / Data Governance
- Access Control / Least Privilege
- Data Integrity
- 情境題 1、2、7、8、14

### L113 機器學習概念

目前附錄章節包含：

- 機器學習基本原理
- 傳統程式與機器學習差異
- 訓練資料角色
- 監督式 / 非監督式 / 強化學習
- 常見任務：迴歸、分類、分群

散落在補強區的相關內容：

- 訓練資料 / 測試資料
- 過擬合 / 欠擬合
- 半監督式學習
- CNN / RNN / LSTM
- KNN、決策樹、SVM
- Softmax
- Wide and Deep
- Precision / Recall
- Data Drift / Concept Drift
- 情境題 5、15、16

### L114 鑑別式 AI 與生成式 AI

目前附錄章節包含：

- 鑑別式 AI 與生成式 AI 基本原理
- 生成式與鑑別式整合應用
- Human-in-the-loop

散落在補強區的相關內容：

- Generative AI vs Discriminative AI
- VAE
- GAN
- Transformer 架構
- CNN vs LSTM vs Transformer
- Prompt Injection vs Prompt Leakage vs Hallucination 中的生成式 AI 風險概念
- 情境題 9、10

### L121 No Code / Low Code 概念

目前附錄章節包含：

- No Code / Low Code 定義
- 適用場景、優缺點、限制
- 灶囍使用 Google Sheet + Apps Script + GitHub Pages 的 Low Code 經驗

散落在補強區的相關內容：

- No Code
- Low Code
- API
- Webhook
- Branch / Router
- Iterator
- Formatter
- Array Aggregator
- Dify 平台元件
- No-Code / Low-Code 平台安全與維護陷阱
- 情境題 20

### L122 生成式 AI 應用領域與工具使用

目前附錄章節包含：

- 生成式 AI 應用領域與常見工具
- ChatGPT、Claude、Codex 分工
- LLM 基礎
- 如何善用生成式 AI 工具
- Prompt Engineering
- 模糊指令風險

散落在補強區的相關內容：

- LLM
- Token
- Context Window
- Temperature
- Chat History
- Prompt Engineering
- Zero-shot / One-shot / Few-shot
- Chain of Thought
- RAG
- Fine-tuning
- PEFT
- LoRA
- Knowledge Distillation
- AI Agent / Agentic AI
- MCP
- Vibe Coding
- 情境題 6、11、12、18

### L123 生成式 AI 導入評估規劃

目前附錄章節包含：

- 生成式 AI 導入評估
- 成本、效益、可行性、ROI
- 生成式 AI 導入規劃
- 分階段實施
- MVP
- 組織溝通與教育訓練
- 生成式 AI 風險管理
- 資料完整性
- RAG 降低幻覺

散落在補強區的相關內容：

- ROI
- TCO
- Feasibility Assessment
- Phased Implementation
- MVP
- Data Governance
- Vendor Lock-in
- Prompt Injection
- Prompt Leakage
- Hallucination
- Data Drift / Concept Drift
- 差分隱私
- RLHF / RFT
- Mode Collapse
- 情境題 3、4、13、19

## 需要回歸原章節的內容

以下內容目前已出現在補強區，但尚未完整回到七章詳讀：

- L111：AI 倫理五原則、AI 基本法 / 金融揭露義務、XAI 三技術、偏見/公平/透明/問責等名詞。
- L112：Data Leakage、半結構化資料、資料整合、資料轉換細節、正規化/標準化、One-hot/Label Encoding、SMOTE、資料完整性、最小權限。
- L113：訓練/測試資料、過擬合/欠擬合、半監督式學習、CNN/LSTM/Transformer、Softmax、KNN/決策樹/SVM、Wide and Deep、Precision/Recall、Data Drift/Concept Drift。
- L114：VAE、GAN、生成式與鑑別式差異的題型比較、生成模型與分類模型的邊界。
- L121：API、Webhook、Dify 元件、Branch/Iterator/Formatter/Aggregator、No/Low-Code 維護與安全限制。
- L122：Token、Context Window、Temperature、Chat History、RAG、Fine-tuning、PEFT、LoRA、Knowledge Distillation、Zero/One/Few-shot、CoT。
- L123：TCO、Vendor Lock-in、Prompt Injection、Prompt Leakage、Hallucination、導入治理、資料治理、風險管理與成本效益陷阱。

## 建議調整順序

建議下一階段不要新增內容，而是把目前內容重整成「七章為主、補強區為輔」：

1. 保留頁首、考試資訊、快速導覽、學習進度。
2. 將「附錄｜課綱七章詳讀」升格為主要學習內容，放在名詞庫之前或直接改為主體。
3. 每一章內固定整理順序：
   - 章節導讀
   - 考試在考什麼
   - 必背名詞
   - 易混淆比較
   - 官方題型
   - 實務案例
   - 常見陷阱
   - 情境練習
4. 原本的「必背名詞庫」拆回各章，不再獨立承載所有名詞。
5. 原本的「易混淆名詞比較」保留為總複習索引，但每組比較要能對應回原章。
6. 原本的「官方題庫對應」保留為總覽，但每題型在章內也要有一份簡版對應。
7. 原本的「高頻考點庫」改為各章內的「高頻補強」，避免同一概念重複出現在三到四個地方。
8. 「考前 30 分鐘速讀」保留獨立區塊，作為最後總複習。
9. 「考試陷阱專區」可保留總索引，但內容應優先回到各章的陷阱小節。
10. 「情境對照練習」可依題目考點拆回各章，最後保留一個混合練習區。

## 下一個最適合實作的任務

下一個最適合實作的任務是：

「只重整內容順序，不改 UI、不改功能、不改題庫文字，把 L112 資料處理與分析概念作為試點章節，將相關補強內容回歸到 L112 章內。」

建議先做 L112，原因：

- L112 相關內容最多、最分散。
- Data Leakage、SMOTE、One-hot、正規化/標準化都是高頻考點。
- L112 可作為七章重整模板。
- 重整 L112 不需要新增功能，只需搬移既有內容。

試點完成後再依同樣格式整理 L113、L122、L123。

## 注意事項

- 下次實作前應先確認是否允許修改 `index.html`。
- 若開始修改網站，務必只做內容順序重整，不新增功能。
- 不應改動 checkbox、`localStorage`、scroll top 等功能。
- 不應重新設計 UI。
- 不應改寫題庫內容與題目答案。
- 搬移內容時需保留原文字，避免引入新的考點錯誤。
