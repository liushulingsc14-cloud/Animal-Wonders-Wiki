# 第二批 Wiki 整理與檢驗紀錄 (Batch 2 Wiki Synthesis Report)

- **紀錄日期**：2026-11-21
- **執行階段**：Graph 階段 2 (第二批 Wiki 整理)
- **依據規範**：AGENTS.md V1.0

---

## 一、本次實際建立之 Wiki 檔案

1. `wiki/hummingbird_backward_flight.md`（蜂鳥為什麼可以在空中懸停，甚至倒退飛行？）
2. `wiki/axolotl_regeneration.md`（墨西哥鈍口螈為什麼能夠再生失去的肢體？）

兩篇文章皆嚴格包含 AGENTS.md 所要求的七大段落架構：
- 動物名稱
- 基本分類
- 冷知識問題
- 簡單解釋
- 科學原理
- 迷思或爭議
- 引用來源

---

## 二、每篇文章使用的來源

1. **蜂鳥篇**：
   - **期刊 / 機構**：*Journal of Experimental Biology*（The Company of Biologists；加州大學柏克萊分校整合生物學系與海法大學）
   - **文獻標題**：*Backward flight in hummingbirds employs unique kinematic adjustments and entails low metabolic cost*
   - **作者**：Nir Sapir, Robert Dudley (2012)
   - **DOI**：https://doi.org/10.1242/jeb.073114
   - **PubMed**：https://pubmed.ncbi.nlm.nih.gov/23014570/ （PMID: 23014570）

2. **墨西哥鈍口螈篇**：
   - **機構 / 期刊**：Max-Planck-Gesellschaft（德國馬克斯·普朗克科學促進學會）與《Nature》
   - **官方發布與論文標題**：
     - 官方新聞：*Decoding the axolotl genome*
     - Nature 原文：*The axolotl genome and the evolution of key tissue formation regulators*
   - **作者**：Sergej Nowoshilow, Elly M. Tanaka, Eugene W. Myers 等跨國團隊 (2018)
   - **官方網址**：https://www.mpg.de/11886639/decoding-the-axolotl-genome
   - **Nature DOI**：https://doi.org/10.1038/nature25458

---

## 三、通過來源核對之核心事實

1. **蜂鳥篇**：
   - 修正過度絕對化說法：確認其他鳥類在受驚擾或禦敵時能短暫向後倒退撲翼，蜂鳥的特徵在於具備「受控且持續（sustained）」倒退飛行能力。
   - 運動學調節：安氏蜂鳥倒飛時維持直立身體姿態、顯著頭部屈曲補償（Head flexion）以鎖定目標、平緩振翅平面，以及振翅頻率上升（~43.8 Hz vs ~39.7 Hz）。
   - 代謝能耗邊界：明確限定該約 20% 能耗差值來自研究團隊對「安氏蜂鳥（*Calypte anna*）在實驗室風洞特定空速條件下」的測量，未任意推廣至全體蜂鳥。

2. **墨西哥鈍口螈篇**：
   - 再生能力範疇：支持附肢（骨骼、肌肉、神經全數修復且無疤痕）、尾巴、脊髓、部分心臟組織與眼睛具備再生潛能。
   - 基因組數據：確認基因組長達約 320 億個鹼基對（32 Gb，人類 10 倍大），重複序列超過 60%，利用 PacBio 長讀取定序與 MARVEL 演算法拼接完成。
   - 發育調控基因演化：確認 *Pax3* 缺失由同源副變體 *Pax7* 代償調控。
   - 觀念邊界澄清：嚴格區分「定序組裝出 32 Gb 巨大基因圖譜」是提供探索再生的分子藍圖與工具，絕非「已完全解密斷肢再生機制」。

---

## 四、待補充資料（移出已驗證事實，清楚標示邊界）

1. **蜂鳥篇**：
   - 經典流場數據（肩關節近 180 度反轉、水平「8 字形」軌跡、上拍貢獻 25%~30% 升力）：屬於流體動力學專門文獻（如 Warrick et al., 2005）之範疇，非本篇 Sapir & Dudley (2012) 原創數據，已列入「待補充獨立流場來源」。
2. **墨西哥鈍口螈篇**：
   - 發育細胞學詳細機制（75% 纖維母細胞參與、成熟細胞去分化為再生芽、位置記憶與維生素 A 酸濃度梯度、人類疤痕組織物理阻礙）：屬於發育細胞學與單細胞轉錄組專門文獻（如 Gerber et al., 2018），非本篇 Nature 2018 基因組定序主報告直接數據，已列入「待補充獨立文獻來源」。

---

## 五、下一階段決策建議

- 第二批兩篇 Wiki 文章已嚴格依據 Loop 修正後的 raw 資料撰寫，所有數據均限定在來源支持的邊界內，無虛構與過度推論。
- **建議正式進入第二批 Wiki 文章驗證階段 (Graph 階段 3)**。
