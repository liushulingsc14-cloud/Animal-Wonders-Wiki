# 第三批原始資料修正與重新驗證報告 (Batch 3 Raw Data Correction - Round 1)

- **紀錄日期**：2026-11-21
- **執行階段**：AGENTS.md Loop 修正機制（第 1 輪修正，上限 3 輪）
- **審核對象**：`raw/raw_batch3_chameleon_color_change.md`（變色龍篇）
- **查證依據**：
  1. *Nature Communications* (DOI: [10.1038/ncomms7368](https://doi.org/10.1038/ncomms7368))
  2. PubMed ([PMID: 25757068](https://pubmed.ncbi.nlm.nih.gov/25757068/))
  3. PMC 全文 ([PMC4366488](https://pmc.ncbi.nlm.nih.gov/articles/PMC4366488/))

---

## 一、問題查證與修正前後對照表

| 項目 | 發現問題 | 修改前敘述 (Before) | 修改後敘述 (After) | 對應原始文獻證據 | 重新驗證結果 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1. PubMed PMID** | 原稿誤植為 25754807 | `收錄於 PubMed: https://pubmed.ncbi.nlm.nih.gov/25754807/ ，PMID: 25754807` | `收錄於 PubMed: https://pubmed.ncbi.nlm.nih.gov/25757068/ ，PMID: 25757068`，並增補 PMC: `https://pmc.ncbi.nlm.nih.gov/articles/PMC4366488/` | 實際開啟 PubMed 官方檢索頁面，該篇論文正確編號確實為 **25757068**。 | **通過** |
| **2. 奈米晶體間距比較基準** | 原稿直接寫成興奮時擴大 30%，未符合原文比較基準 | `細胞主動使鳥嘌呤奈米晶格間距擴張約 30%` | `在平靜放鬆（relaxed）狀態下，表層虹彩細胞中的鳥嘌呤奈米晶體間距，平均比興奮（excited）狀態小約 30%（即以興奮狀態之間距為基準時，平靜時之間距小約 30%）。避免簡化寫成以平靜為基底之「興奮時增加 30%」。` | 原文敘述："We find that the distance among the guanine nanocrystals within S-iridophores is on average ~30% smaller in the relaxed state than in the excited state." | **通過** |
| **3. 深層細胞熱防護描述之確定性** | 原稿將防止過熱寫成確定生理效果 | `這項物理特性為生活在高溫烈日環境（如馬達加斯加）的變色龍提供了被動的熱防護（Passive thermal protection），降低體內吸收過量熱能的風險。` | `這項物理反射特性「可能為生活在高溫強光環境下的變色龍提供被動熱防護（potentially providing passive thermal protection）」，有助於減少吸收太陽輻射熱。然而論文強調此為光學反射上的潛在優勢，不得描述為已在活體完全證實之確定生理調控效果。` | 原文敘述："potentially providing passive thermal protection." 論文僅確證光譜反射率，未在活體全面測量體溫恆定生理貢獻。 | **通過** |
| **4. 物種範圍界定** | 需確保豹變色龍研究結果不被外推至全體變色龍 | 已有初步標記，但需更嚴格強化物種邊界與對比 | 明確於標題、摘要與邊界章節指出：研究嚴格基於「豹變色龍（*Furcifer pardalis*）」，全體變色龍科有約 200 種且生態極其多樣（如枯葉變色龍屬幾乎不具鮮豔變色能力），嚴禁外推至全體變色龍。 | 原文 Methods 與 Results 明確以 *Furcifer pardalis* 為核心實驗模型。 | **通過** |
| **5. 偽裝功能之客觀描述** | 避免將「不是只為了偽裝」誤寫為「完全不具偽裝功能」 | 已有區分，但需嚴防極端化解讀 | 增設專門小節強調：「變色不只是為了偽裝」$\neq$「完全不具偽裝功能」；論文強調放鬆時的隱蔽偽裝與興奮時的醒目社交是同時存在的生存權衡（Trade-off），不可全盤否定偽裝功能。 | 原文明載："active color change is not simply for camouflage... the superficial layer provides active color changes for social displays and camouflage." | **通過** |

---

## 二、尚待補充之項目說明 (Pending Items)

為維持最高科學求真標準，以下延伸項目在本次修正中明確列為【待補充獨立來源】：
1. **活體神經生化調控途徑**：大腦視覺刺激引發表層虹彩細胞晶格膨脹/收縮的具體神經傳導物質與荷爾蒙受體（標記為待補充獨立神經生物學來源）。
2. **天敵視覺模型下的偽裝效率量化**：不同掠食者（鳥類、蛇類）視覺感知模型下的實測偽裝數據（標記為待補充視覺生態學來源）。
3. **活體深層細胞體溫調節實測**：深層 D-iridophores 在活體動物生理體溫維持上的實際貢獻度（標記為待補充活體生理熱學來源）。

---

## 三、Loop 修正與重新驗證總結

1. **修正輪次**：第 1 輪修正（單一問題上限 3 輪）。
2. **重新驗證結果**：所有 5 項修正問題均已完成 PMC/PubMed/Nature 原文的實際核對，修正後的 raw 檔案完全忠實於文獻數據與原始比較基準，**全數通過驗證 (All Passed)**。
3. **下一步建議**：第三批 raw/ 原始資料已達到極高之客觀度與嚴謹度，**建議正式進入第三批 Wiki 文章整理階段 (Graph 階段 2)**。
