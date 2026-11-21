# 參考文獻失效連結局部修正報告 (問題編號：L01)

**報告日期**：2026-11-21  
**問題編號**：L01  
**問題類型**：文獻外部超連結失效 (HTTP 404 Not Found)  
**發現方式**：使用者實際於 Microsoft Edge 瀏覽器進行人工操作與外鏈點擊測試  
**遵循規範**：`AGENTS.md` - 第 3 節 資料來源可信度、第 5 節 引用追溯與檢查標準、第 7 節 Loop 局部修復機制  
**執行狀態**：**網址修正完成 / 檔案同步完畢 / 程式與結構驗證 PASS / 未執行 Git Commit**

---

## 一、問題描述與修正網址對照

在使用者人工檢驗 [slides/index.html](file:///c:/Users/maggi/OneDrive/桌面/Animal-Wonders-Wiki/slides/index.html) 第 12 頁參考文獻與第 4、5 頁頁尾來源連結時，發現海獺權威文獻 Sea Otter Savvy 之舊版新聞路徑出現 404 Not Found。經使用者重新查得官方最新永久文章網址後完成全面局部替換。

- **文獻標題**：Sea Otter Paw Holding: A Reality Check
- **作者**：Gena Bentall（Sea Otter Savvy 總監暨資深海洋野外生物學家）
- **發布機構**：Sea Otter Savvy（USFWS / CDFW / 蒙特雷灣水族館合作倡議）
- **原本失效網址**：`https://www.seaottersavvy.org/news/377-sea-otter-paw-holding-a-reality-check`
- **更新後官方網址**：`https://www.seaottersavvy.org/sea-otter-paw-holding-a-reality-check`

---

## 二、實際修改檔案與行號位置清單

本次僅修正 URL 字串，嚴格保留原有之全部科學內容、排版結構與互動邏輯：

| 檔案路徑 | 行號位置（概估） | 修改前內容 | 修改後內容 | 修改性質 |
| :--- | :---: | :--- | :--- | :---: |
| `slides/index.html` | 約 633 行 (Slide 4 頁尾) | `href=".../news/377-sea-otter-..."` | `href="https://www.seaottersavvy.org/sea-otter-paw-holding-a-reality-check"` | 投影片頁尾數據來源超連結更新 |
| `slides/index.html` | 約 683 行 (Slide 5 頁尾) | `href=".../news/377-sea-otter-..."` | `href="https://www.seaottersavvy.org/sea-otter-paw-holding-a-reality-check"` | 投影片頁尾數據來源超連結更新 |
| `slides/index.html` | 約 1013 行 (Slide 12 表格) | `href=".../news/377-sea-otter-..."` | `href="https://www.seaottersavvy.org/sea-otter-paw-holding-a-reality-check"` | 結業文獻清單超連結更新 |
| `wiki/sea_otter_holding_hands.md` | 約 64 行 (第七節引用來源) | `- **原始網址**：.../news/377-...` | `- **原始網址**：https://www.seaottersavvy.org/sea-otter-paw-holding-a-reality-check` | Wiki 知識庫原始來源網址同步 |
| `raw/raw_batch1_sea_otter_holding_hands.md` | 約 10 行 (第一節來源資訊) | `- **原始網址**：.../news/377-...` | `- **原始網址**：https://www.seaottersavvy.org/sea-otter-paw-holding-a-reality-check` | Raw 原始資料記錄網址同步 |

---

## 三、驗證方式與執行結果

### 1. 網址字串全庫掃描檢驗
- 執行全庫搜尋（`Select-String -Pattern "377-sea-otter"`）：在 `slides/index.html`、`wiki/` 與 `raw/` 中，舊版失效路徑出現次數為 **0**。
- 執行新網址搜尋（`Select-String -Pattern "sea-otter-paw-holding-a-reality-check"`）：確認上述 5 個目標位置均正確且精確更新為現行官方網址。

### 2. 簡報程式與結構回歸檢驗 (靜態程式檢查)
經執行自動化回歸檢驗腳本（`verify_html_round2.ps1`），確認 URL 修正未對簡報結構造成任何副作用：
- **總頁數**：嚴格維持 12 頁（PASS）。
- **導航與進度指示器**：按鈕、計數器與 12 個進度點正常（PASS）。
- **五道 Quiz 結構與答案**：答案分佈嚴格維持為 **Q1=B, Q2=B, Q3=B, Q4=C, Q5=B**，互動按鈕與回饋區塊結構完整（PASS）。
- **JavaScript 語法與括號平衡**：大括號 43/43、圓括號 48/48 完全平衡閉合（PASS）。

---

## 四、專案其他參考文獻 URL 之檢查狀態標示

依據沙盒隔離規範與真實測試原則，Coding Agent 在沙盒內無法主動向外網發送 HTTP 請求。因此，**嚴禁虛報或冒稱測試通過**，以下將全案所有文獻 URL 之驗證狀態明確客觀標示如下：

| 來源主題 / 物種 | 文獻識別碼 / 原始 URL | 語法結構格式 | 實體連線驗證狀態 | 說明與備註 |
| :--- | :--- | :---: | :---: | :--- |
| **海獺 (鼬科)** | `https://www.seaottersavvy.org/sea-otter-paw-holding-a-reality-check` | 合規 | **使用者人工測試通過** | 使用者實際以 Edge 開啟並確認有效（已修復 404 問題） |
| **章魚 (八腕目)** | `https://www.smithsonianmag.com/science-nature/ten-wild-facts-about-octopuses-they-have-three-hearts-big-brains-and-blue-blood-7625828/` | 合規 | **未連線驗證** | 受沙盒無外網限制；URL 格式正確，待使用者於瀏覽器人工點擊查驗 |
| **安氏蜂鳥 (鳥綱)** | `https://doi.org/10.1242/jeb.073114` | 合規 | **未連線驗證** | 受沙盒無外網限制；國際標準 DOI 解析格式正確，待使用者人工點擊查驗 |
| **墨西哥鈍口螈 (兩棲綱)** | `https://doi.org/10.1038/nature25458` | 合規 | **未連線驗證** | 受沙盒無外網限制；Nature 正式 DOI 解析格式正確，待使用者人工點擊查驗 |
| **墨西哥鈍口螈 (機構報導)**| `https://www.mpg.de/11886639/decoding-the-axolotl-genome` | 合規 | **未連線驗證** | 受沙盒無外網限制；馬克斯普朗克學會官方新聞路徑正確，待使用者人工點擊查驗 |
| **豹變色龍 (爬蟲綱)** | `https://doi.org/10.1038/ncomms7368` | 合規 | **未連線驗證** | 受沙盒無外網限制；Nature Communications DOI 解析格式正確，待使用者人工點擊查驗 |
| **PubMed 索引資料庫** | `https://pubmed.ncbi.nlm.nih.gov/23014570/`<br>`https://pubmed.ncbi.nlm.nih.gov/25757068/` | 合規 | **未連線驗證** | Wiki 輔助索引；NCBI 標準路徑格式正確，待使用者人工點擊查驗 |
| **PMC 開放取用資料庫** | `https://pmc.ncbi.nlm.nih.gov/articles/PMC4366488/` | 合規 | **未連線驗證** | Wiki 輔助全文來源；格式正確，待使用者人工點擊查驗 |

---

## 五、執行邊界與結語

- 本次修改嚴格限於 URL 更新，未修改任何科學陳述、科普字詞、排版樣式或 JS 邏輯。
- 未執行 Git Commit。
- 專案已就緒，等待使用者指示後續步驟。
