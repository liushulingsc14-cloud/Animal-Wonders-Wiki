# 獨立科學審查後第一輪 Loop 修正報告 (raw/ 與 wiki/ 修正)

**報告日期**：2026-11-21  
**執行階段**：Graph 階段 7 退回 Graph 階段 2 (Wiki 整理) 之第一輪 Loop 修正 (Round 1)  
**遵循規範**：`AGENTS.md` - 第 6 節 Graph 工作流、第 7 節 Loop 修復機制與停止條件  
**本階段目標**：修正 `raw/` 與 `wiki/` 中存在的科學事實、引用與過度推論問題，**暫不修改 HTML**。  
**執行狀態**：9 項問題（P02, P03, P04, P05, P06, P07, P09, P10, P11）已全數完成修正與結構核驗。

---

## 一、修正問題對照表 (P02～P11 修改前後對照)

### 1. P02：章魚循環系統（體心停搏疲勞機制）
- **修改檔案**：`wiki/octopus_three_hearts.md`（段落四、段落五）
- **修正重點**：移除「傷心臟」及「全身立即完全缺氧、無氧力竭」等缺乏直接證據之推論；忠實回歸 Smithsonian 原文「exhausts them」描述。
- **修改前**：
  > 「這導致章魚游泳時極度費力且很快就缺氧力竭，因此牠們在海床上更偏好運用柔軟的腕足一步一步漫步攀爬...」  
  > 「由於游泳當下全身重要器官無法獲得充足的動脈血灌流，章魚會迅速陷入無氧代謝與疲憊狀態。」
- **修改後**：
  > 「體心暫停搏動限制了器官血液循環輸送，導致游泳極度消耗體能且容易疲勞力竭（exhausts them），因此牠們在日常活動中更偏好運用柔軟的腕足在海床上漫步攀爬，只有在逃避掠食者或緊急時刻才會全力噴水游泳。」  
  > 「這項生理特性顯著限制了游泳過程中的全身血液輸送與循環效率，使得章魚游泳極度消耗體力、容易迅速感到疲勞力竭（exhausts them）。為了節省體能並維持穩定的生理機能，章魚在演化上發展出以腕足在海床爬行（Crawling）為主的日常移動習性。」
- **對應來源證據**：Smithsonian Magazine (2013): *"The organ heart actually stops beating when the octopus swims, explaining the species' penchant for crawling rather than swimming, which exhausts them."*

---

### 2. P03：豹變色龍體色（結構色與色素細胞共同作用）
- **修改檔案**：`wiki/chameleon_color_change.md`（段落四、段落五）
- **修正重點**：說明晶體排列造成的結構色，以及黃色、紅色色素細胞的共同疊加作用；不得宣稱所有鮮豔顏色都完全由晶體反射產生。
- **修改前**：
  > 「而黃、綠、藍、紅等鮮豔色彩的快速切換，是由皮膚中的結構色（Structural coloration）決定的。」  
  > 「透過像調校微型百葉窗一樣調整奈米晶體之間的距離，就能像稜鏡一樣瞬間改變皮膚反射的光線顏色！」
- **修改後**：
  > 「而鮮豔動態的體色轉變，並非單一色素或單純晶體的功勞，而是表層虹彩細胞產生的『結構色（Structural coloration）』與上層黃色/紅色色素細胞（Xanthophores / Erythrophores）相互疊加的綜合結果。」  
  > 「牠們的皮膚同時結合了微型『光子晶體』的物理反射與真皮色素細胞的過濾！透過像微型百葉窗般調節表層奈米晶體的間距，反射出不同波長的光線（如藍光或紅光），再與皮膚表層的黃色及紅色色素細胞相互疊加，在短短數分鐘內調配出驚人的體色變化！」
- **對應來源證據**：*Nature Communications* (Teyssier et al., 2015): *"When skin is relaxed, the crystals selectively reflect short wavelengths (blue). Combined with yellow pigments in overlying xanthophores, the skin appears green. In the excited state, crystal spacing is larger, shifting selective reflection to longer wavelengths (yellow, orange, or red)."*

---

### 3. P04：墨西哥鈍口螈再生（無疤痕再生用詞客觀化）
- **修改檔案**：`wiki/axolotl_regeneration.md`（段落三、段落四）
- **修正重點**：刪除「所有情況下功能完美」、「完全不留任何難看/永久性疤痕」等過度絕對的宣稱，保留科學支持的高組織再生能力。
- **修改前**：
  > 「墨西哥鈍口螈失去四肢後為什麼能完美長回？」  
  > 「骨骼、肌肉與神經全數復原，且完全不留難看的疤痕...」
- **修改後**：
  > 「墨西哥鈍口螈失去四肢後為什麼能高度長回並恢復機能？」  
  > 「牠能高度重新長出包含骨骼、肌肉與神經的完整新肢體，恢復運動功能，且在多數健康情況下幾乎不形成哺乳動物常見的永久性纖維化疤痕...」
- **對應來源證據**：Max Planck Society (2018) & *Nature* (2018): 描述附肢各組織之重建能力與修復潛能（restoration of functional limb and scar-free wound healing），發育生物學界客觀保留極端感染或異常創傷下可能產生形態畸變之空間。

---

### 4. P05：Pax3 與 Pax7 基因演化代償
- **修改檔案**：`raw/raw_batch2_axolotl_regeneration.md`、`wiki/axolotl_regeneration.md`（段落五、段落七）
- **修正重點**：精確描述 Pax3 缺失與 Pax7 相關發育功能，不得宣稱已證明 Pax7 完整取代 Pax3 的全部功能。
- **修改前**：
  > 「其功能完全由其同源副變體基因 Pax7 取代並代償調控。」  
  > 「進一步分析證實，其同源副變體基因 Pax7 在演化過程中接管了關鍵功能，承擔起組織形成與發育的代償調控角色。」
- **修改後**：
  > 「研究顯示其同源副變體基因 Pax7 承擔起重要的組織形成發育調控功能（論文指出 Pax7 代償了神經與肌肉發育的關鍵角色，但並未宣稱已證明 Pax7 完整取代 Pax3 的全部功能）。」  
  > 「研究顯示，其同源副變體基因 Pax7 在演化中承擔起組織形成與發育的重要調控角色（論文指出 Pax7 代償了神經與肌肉發育的關鍵功能，但學界並未將其定論為已證明完整取代 Pax3 的所有功能）。」
- **對應來源證據**：*Nature* (Nowoshilow et al., 2018): *"Analysis of the genome identified evolutionary changes in developmental regulators, including the apparent absence of Pax3, whose essential roles in muscle and neural development are compensated by its paralogue Pax7."*

---

### 5. P06：安氏蜂鳥風洞飛行能耗
- **修改檔案**：`wiki/hummingbird_backward_flight.md`（段落三、段落四、段落五）
- **修正重點**：保留安氏蜂鳥特定風洞實驗中倒飛耗氧率低於懸停約 20% 的測量結果；移除所有自然情況下倒飛必然更省力的推廣推論。
- **修改前**：
  > 「而且在特定實驗條件下，倒著飛竟然比在原地懸停更省力？」  
  > 「不得任意推論為所有蜂鳥種類在一切自然飛行情境下皆具備相同數值。」
- **修改後**：
  > 「而且在特定風洞實驗中，安氏蜂鳥倒著飛的代謝耗能為什麼比原地懸停更低？」  
  > 「這是因為鳥類原地懸停時缺乏前向氣流誘導升力，本身就是極度耗能的狀態；這項實驗打破了『倒飛必然比懸停更費力』的直覺假說，但不能隨意推廣為蜂鳥在自然界的所有飛行情境下倒飛都普遍更省力。」  
  > 「原地懸停本身缺乏前進氣流輔助升力、代謝極為劇烈，風洞倒飛產生相對氣流有助維持升力，但不得任意推論為所有蜂鳥種類在自然界一切情境下倒飛都具有普遍省力優勢。」
- **對應來源證據**：*Journal of Experimental Biology* (Sapir & Dudley, 2012): 原文測量僅在特定風洞空速條件下測得，且原地懸停（hovering）因氣流誘導升力不足本身代謝率極高，不能等同於野外覓食倒退皆比前飛或停歇省力。

---

### 6. P07：海獺行為細節清理
- **修改檔案**：`raw/raw_batch1_sea_otter_holding_hands.md`、`wiki/sea_otter_holding_hands.md`（段落五）
- **修正重點**：移除缺乏來源支持的群體防範大白鯊等細節；母幼巨藻固定行為移至待補充說明區域；保留可靠來源支持的群體休息（竹筏群）及巨藻定錨防漂行為。
- **修改前**：
  > 「群體規模小則十幾隻，大則可達數百隻，有助於集體警戒掠食者。」  
  > 「母海獺下水覓食前，也會用巨藻將幼崽包裹好固定在水面上。」
- **修改後**：
  > 「群體規模從十幾隻到數百隻不等，聚集休息是牠們在開闊海面上重要的群體生活型態。」  
  > 刪除正文中的母幼包裹描述，改設延伸說明：「*【延伸生態觀察說明】*：部分自然科普常提及『母海獺潛水覓食前會用巨藻包裹幼崽固定於水面』，此項育幼觀察在本次核心文獻中未載有量化行為數據，特此標記為【待補充獨立海洋哺乳動物文獻來源】。」
- **對應來源證據**：Sea Otter Savvy (Bentall, 2020): 原文僅記載 *"Wild sea otters form resting groups called rafts and often wrap themselves in strands of giant kelp to stay anchored and avoid drifting away with ocean currents."*，未載明集體警戒大白鯊或育幼固定比例。

---

### 7. P09：巨藻構造術語修正（固著器 Holdfast）
- **修改檔案**：`raw/raw_batch1_sea_otter_holding_hands.md`、`wiki/sea_otter_holding_hands.md`（段落四、段落五）
- **修正重點**：將植物學/藻類學錯誤之「根部深植海床」修正為「固著器附著於岩石海床基質」。
- **修改前**：
  > 「巨藻在海底扎根極深，就像天然的海中船錨...」  
  > 「巨藻根部牢牢附著於岩礁海床上，能發揮如錨繩般的固定作用...」
- **修改後**：
  > 「巨藻基部的固著器牢固抓附於岩石海床上，就像天然的海中船錨，能有效防止海獺隨洋流漂散。」  
  > 「巨藻為大型褐藻，其基部的『固著器（Holdfast）』牢固抓附於岩礁海床上，使長達數十公尺的巨藻條成為天然纜繩，發揮如錨一般的固定作用，防止海獺被海流沖向外海。」
- **對應來源證據**：大型褐藻（如 *Macrocystis pyrifera*）不具備高等植物之真根構造，其「固著器 (Holdfast)」專司基質抓附，符合藻類學生態常識。

---

### 8. P10：變色龍變色時間量化描述
- **修改檔案**：`wiki/chameleon_color_change.md`（段落三、段落四、段落五）
- **修正重點**：核對原始論文中的時間尺度，將沒有直接支持的「數秒內/瞬間」改為符合論文的描述「數分鐘內（within a couple of minutes）」。
- **修改前**：
  > 「牠們究竟是如何在短短數秒鐘內變出鮮豔色彩的？」  
  > 「才會瞬間換上高對比的明亮黃色、橙色或紅色『戰袍』...」  
  > 「瞬間展現極度醒目的色彩。」
- **修改後**：
  > 「牠們究竟是如何在數分鐘之內迅速切換鮮豔色彩的？」  
  > 「才會在短短數分鐘之內換上高對比的明亮黃色、橙色或紅色『戰袍』來展現實力...」  
  > 「在數分鐘內（within a couple of minutes）展現出耀眼奪目的黃色、橙色或鮮紅色社交體色。」
- **對應來源證據**：*Nature Communications* 2015 (PMC4366488): *"This process occurs within a couple of minutes and is fully reversible."*（論文中數秒係指取樣組織固定時間）。

---

### 9. P11：Smithsonian 文章發表與更新日期
- **修改檔案**：`raw/raw_batch1_octopus_hearts.md`、`wiki/octopus_three_hearts.md`（段落七）
- **修正重點**：更正原始發表日期為 2013-10-31，並載明 2024-03-13 更新。
- **修改前**：
  > `- **發布/更新日期**：2012-10-31（經科學新知持續更新）`
- **修改後**：
  > `- **發布/更新日期**：原始發表 2013-10-31；更新日期 2024-03-13`
- **對應來源證據**：Smithsonian Magazine 官方網頁原件載明原始發表日期為 October 31, 2013，最新更新為 March 13, 2024。

---

## 二、實際修改檔案清單

### 原始資料庫 (`raw/`)：共 3 個檔案
1. `raw/raw_batch1_octopus_hearts.md` (P11)
2. `raw/raw_batch1_sea_otter_holding_hands.md` (P07, P09)
3. `raw/raw_batch2_axolotl_regeneration.md` (P05)

### Wiki 知識庫 (`wiki/`)：共 5 個檔案
1. `wiki/octopus_three_hearts.md` (P02, P11)
2. `wiki/sea_otter_holding_hands.md` (P07, P09)
3. `wiki/hummingbird_backward_flight.md` (P06)
4. `wiki/axolotl_regeneration.md` (P04, P05)
5. `wiki/chameleon_color_change.md` (P03, P10)

---

## 三、問題收斂與驗證狀態判定

| 問題編號 | 處理狀態 | raw/ 是否已修正 | Wiki 是否已修正 | 待後續 HTML 同步 |
| :---: | :---: | :---: | :---: | :---: |
| **P02** | **已完成修正** | 原文無問題 | 已修正段落四、五 | 需同步修正 Slide 3 與 Quiz 1 |
| **P03** | **已完成修正** | 原文無問題 | 已修正段落四、五 | 需同步修正 Slide 10 |
| **P04** | **已完成修正** | 原文無問題 | 已修正段落三、四 | 需同步修正 Slide 8、12 |
| **P05** | **已完成修正** | 已修正段落三 | 已修正段落五、七 | 需同步修正 Slide 9、12 |
| **P06** | **已完成修正** | 原文無問題 | 已修正段落三、四、五 | 需同步修正 Slide 7 |
| **P07** | **已完成修正** | 已修正段落三 | 已修正段落四、五 | 需同步修正 Slide 5 |
| **P09** | **已完成修正** | 已修正段落三 | 已修正段落四、五 | 需同步修正 Slide 5 |
| **P10** | **已完成修正** | 原文無問題 | 已修正段落三、四、五 | 需同步修正 Slide 10 |
| **P11** | **已完成修正** | 已修正段落一 | 已修正段落七 | 需同步修正 Slide 2、3、12 |

### 尚待處理之問題（限於 HTML 展示層）：
- **P01**（第 1、12 頁「100% 已查證」宣稱過強）：屬於 HTML 專屬問題，留待後續 HTML 修正階段處理。
- **P08**（第 11 頁變色龍近紅外線反射熱防護需明確為推論假說）：屬於 HTML 專屬問題，留待後續 HTML 修正階段處理。
- **P12**（第 7、9～11 頁 LaTeX 符號與術語通俗化）：屬於 HTML 專屬問題，留待後續 HTML 修正階段處理。

---

## 四、Wiki 結構與重新驗證建議

- **七大段落完整性**：經自動化結構腳本比對，五篇 Wiki 均完整具備「一、動物名稱」、「二、基本分類」、「三、冷知識問題」、「四、簡單解釋」、「五、科學原理」、「六、迷思或爭議」、「七、引用來源」七大必備結構，未發生段落缺失。
- **重新驗證需求**：
  - 本次對 `wiki/` 進行了關鍵科學陳述修正，依據 `AGENTS.md` 工作流，建議在正式將修正同步至 HTML 之前，執行一次精簡的 **Wiki 正式驗證**，以確保知識庫在進入 HTML 渲染前完全處於嚴格一致且無瑕疵之狀態。

---

## 五、遵守邊界與狀態

- **未修改** `slides/index.html`、`slides/outline.md`。
- **未修改** `AGENTS.md`。
- **未執行** `git commit`。
- **未自動開始** HTML 修正或宣稱全案通過。
- 本階段已完成並停止，等待使用者指示。
