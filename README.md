# 2026 加拿大出國訪廠會議紀錄庫 (`2026CA_meeting`)

🌐 **線上會議記錄網頁選單（免看 `.md`、支援 TXT / Word (`.docx`) / PDF 匯出）：**
- **直接訪問網址 (GitHub Pages)**：**[https://delphicchen.github.io/2026CA_meeting/](https://delphicchen.github.io/2026CA_meeting/)**
- **訪問密碼**：`8021111`

---

本儲存庫依**嚴格時間順序（Chronological Order：`YYYYMMDD_HHMM_<客戶名稱>`）**存放 2026 年 10 月加拿大出國拜訪客戶之會議紀錄、原生聽覺模態完整逐段底稿與結構化數據資料，並提供互動式 HTML 網頁選單（[`index.html`](./index.html)）供不熟悉 Markdown 之同仁直接於瀏覽器閱讀及一鍵匯出為 **TXT、Word (`.docx`)、PDF**。

> [!TIP]
> **時間順序命名規範（避免同日多場會議依字母排序錯亂）**
> 由於同一天有多場拜訪（例如 `2026-10-19` 上午 `09:08` 拜訪 `Terra Nova`、中午 `11:57` 拜訪 `Cascadia`，若僅以日期+客戶名排序，`cascadia` 會在 `terra_nova` 之前），因此本儲存庫採用 **`YYYYMMDD_HHMM_<客戶名稱>`** 作為歸檔排序前綴，確保檔案系統預設排序即為真實訪廠時間順序。

---

## 📅 訪廠行程與會議時間軸總覽 (Chronological Trip Schedule)

| 場次順序 | 日期 | 當地時間 | 拜訪客戶 / 機構 | 地點 | 時間序歸檔目錄 | 狀態 |
| :---: | :---: | :---: | :--- | :--- | :--- | :---: |
| **01** | **2026-10-19** | **09:08 – 10:53 PDT** | **Terra Nova Steel** (Doug / Chris 及貿易商團隊) | Richmond, BC, Canada | [`20261019_0908_terra_nova/`](./20261019_0908_terra_nova/) | ✅ 已完成聽覺解析與歸檔 |
| **02** | **2026-10-19** | **11:57 – 12:48 PDT** | **Cascadia Metals** (Jim Ritchie / Mark / Amy / Philip 及貿易商團隊) | Vancouver, BC, Canada | [`20261019_1157_cascadia/`](./20261019_1157_cascadia/) | ✅ 已完成聽覺解析與歸檔 |
| **03** | **2026-10-21** | **09:09 – 10:31 MDT** | **Price Steel** (Dwayne / Rod 及 Salzgitter 團隊) | Edmonton, AB, Canada | [`20261021_0909_price_steel/`](./20261021_0909_price_steel/) | ✅ 已完成聽覺解析與歸檔 |
| **04** | **2026-10-21** | **11:21 – 12:31 MDT** | **Carry Steel** (Richard 及貿易商團隊) | Edmonton, AB, Canada | [`20261021_1121_carry_steel/`](./20261021_1121_carry_steel/) | ✅ 已完成聽覺解析與歸檔 |
| **05** | **2026-10-21** | **14:42 – 15:54 MDT** | **Russel Metals** (Jim / Devon / Steve 及 Salzgitter 團隊) | Edmonton, AB, Canada | [`20261021_1442_russel_steel/`](./20261021_1442_russel_steel/) | ✅ 已完成聽覺解析與歸檔 |
| **06** | **2026-10-22** | **14:04 – 15:56 MDT** | **Varsteel Ltd.** (Jason / Kevin 及 thyssenkrupp 團隊) | Lethbridge, AB, Canada | [`20261022_1404_varsteel/`](./20261022_1404_varsteel/) | ✅ 已完成聽覺解析與歸檔 |

---

## 📁 場次 01：Terra Nova Steel（2026-10-19 09:08 – 10:53 PDT）

### 1. 檔案清單與用途說明
- **時間序歸檔目錄 [`20261019_0908_terra_nova/`](./20261019_0908_terra_nova/)**（亦同步保留於根目錄 `./`）：
  1. **[`20261019_0908_01_terra_nova_meeting_report.md`](./20261019_0908_terra_nova/20261019_0908_01_terra_nova_meeting_report.md)**（同根目錄 [`20261019_terra_nova_meeting_report.md`](./20261019_terra_nova_meeting_report.md)，9.5 KB）
     - **結構化重點與數據資料庫**：依主題分類之精華版會議記錄（客戶全年 20,000 噸採購結構、TRQ 豁免清單、A516-70 中韓價格拆解、技術亮點、Action Items）。
  2. **[`20261019_0908_02_terra_nova_audio_report.md`](./20261019_0908_terra_nova/20261019_0908_02_terra_nova_audio_report.md)**（同根目錄 [`terra_nova_20261019_audio_report.md`](./terra_nova_20261019_audio_report.md)，47 KB）
     - **完整音訊解析報告**：包含執行摘要（TRQ/AD 規定、規格與價格對比表、採購決策）與全部 21 段時間軸詳細紀錄。
  3. **[`20261019_0908_03_terra_nova_raw_notes.md`](./20261019_0908_terra_nova/20261019_0908_03_terra_nova_raw_notes.md)**（同根目錄 [`20261019_terra_nova_raw_notes.md`](./20261019_terra_nova_raw_notes.md)，81 KB）
     - **未刪減分段聽覺完整底稿**：完整保留 `00:00:00` – `01:44:49` 所有中英文原句引述、台下中鋼團隊中文內部討論、數據、價格與時間軸，供後續轉換任何報告格式使用。
  4. **[`20261019_0908_notes.txt`](./20261019_0908_terra_nova/20261019_0908_notes.txt)**（同根目錄 [`20261019.txt`](./20261019.txt)）
     - 現場隨手重點筆記（TRQ 豁免尺寸與官方連結）。

---

## 📁 場次 02：Cascadia Metals（2026-10-19 11:57 – 12:48 PDT）

### 1. 檔案清單與用途說明
- **時間序歸檔目錄 [`20261019_1157_cascadia/`](./20261019_1157_cascadia/)**（亦同步保留於根目錄 `./`）：
  1. **[`20261019_1157_01_cascadia_meeting_report.md`](./20261019_1157_cascadia/20261019_1157_01_cascadia_meeting_report.md)**（同根目錄 [`20261019_cascadia_meeting_report.md`](./20261019_cascadia_meeting_report.md)）
     - **結構化重點與數據資料庫**：Cascadia 美加月用量 40,000 噸規模拆解、10 Gauge GI/GA 不計價急迫採購需求、Stelco 停產鍍鋅/冷軋每月 3.5 萬噸缺口、中鋼冷軋全尺寸優勢（1660/1272）、台韓海運價差（Swire vs. Saga）與 Amazon AI 資料中心供應鏈（Johnson Controls / IEM）。
  2. **[`20261019_1157_02_cascadia_audio_report.md`](./20261019_1157_cascadia/20261019_1157_02_cascadia_audio_report.md)**（同根目錄 [`cascadia_20261019_audio_report.md`](./cascadia_20261019_audio_report.md)）
     - **完整音訊解析報告**：包含與會人員識別、核心商情摘要與全部 17 段（`00:00` – `50:32`）時間軸詳細紀錄。
  3. **[`20261019_1157_03_cascadia_raw_notes.md`](./20261019_1157_cascadia/20261019_1157_03_cascadia_raw_notes.md)**（同根目錄 [`20261019_cascadia_raw_notes.md`](./20261019_cascadia_raw_notes.md)）
     - **未刪減分段聽覺完整底稿**：完整保留 17 段對話與英文原句引述（Quotes）、量化數據總表與細節。
  4. **[`20261019_1157_04_cascadia_structured_data.json`](./20261019_1157_cascadia/20261019_1157_04_cascadia_structured_data.json)**
     - **結構化 JSON 資料庫**：與會名單、關鍵指標、各產品線與北美鋼廠情報結構化資料。

---

## 📁 場次 03：Price Steel（2026-10-21 09:09 – 10:31 MDT）

### 1. 檔案清單與用途說明
- **時間序歸檔目錄 [`20261021_0909_price_steel/`](./20261021_0909_price_steel/)**（亦同步保留於根目錄 `./`）：
  1. **[`20261021_0909_01_price_steel_meeting_report.md`](./20261021_0909_price_steel/20261021_0909_01_price_steel_meeting_report.md)**（同根目錄 [`20261021_price_steel_meeting_report.md`](./20261021_price_steel_meeting_report.md)）
     - **結構化重點與數據資料庫**：四合一多重認證鋼板（`38W/44W + A36 + SA36 + API 650 Class 3`）MTR 標示與鋼板噴印要求、加西 30,000 噸常壓儲槽市場與「Pacific Link」1,500km 新油管商機、中鋼 `1/4" × 10'` 薄寬板與唯一海外供應 `Cat 4` 優勢、溫哥華至愛德蒙頓內陸接駁成本（CAD $185~$195/MT）及渥太華擬再砍 TRQ 獨家內幕。
  2. **[`20261021_0909_02_price_steel_audio_report.md`](./20261021_0909_price_steel/20261021_0909_02_price_steel_audio_report.md)**（同根目錄 [`price_steel_20261021_audio_report.md`](./price_steel_20261021_audio_report.md)）
     - **完整音訊解析報告**：包含執行摘要與全部 28 段（`00:00:00` – `01:22:29`）時間軸詳細紀錄。
  3. **[`20261021_0909_03_price_steel_raw_notes.md`](./20261021_0909_price_steel/20261021_0909_03_price_steel_raw_notes.md)**（同根目錄 [`20261021_price_steel_raw_notes.md`](./20261021_price_steel_raw_notes.md)）
     - **未刪減分段聽覺完整底稿**：完整保留 28 段對話、英文原句引述（Quotes）、中鋼內部中文討論與量化數據細節。
  4. **原生 Word 檔案（`.docx`）**：
     - [`20261021_0909_Price_Steel_Meeting_Report.docx`](./20261021_0909_price_steel/20261021_0909_Price_Steel_Meeting_Report.docx)
     - [`20261021_0909_Price_Steel_Audio_Report.docx`](./20261021_0909_price_steel/20261021_0909_Price_Steel_Audio_Report.docx)
     - [`20261021_0909_Price_Steel_Raw_Notes.docx`](./20261021_0909_price_steel/20261021_0909_Price_Steel_Raw_Notes.docx)

---

## 📁 場次 04：Carry Steel（2026-10-21 11:21 – 12:31 MDT）

### 1. 檔案清單與用途說明
- **時間序歸檔目錄 [`20261021_1121_carry_steel/`](./20261021_1121_carry_steel/)**（亦同步保留於根目錄 `./`）：
  1. **[`20261021_1121_01_carry_steel_meeting_report.md`](./20261021_1121_carry_steel/20261021_1121_01_carry_steel_meeting_report.md)**（同根目錄 [`20261021_carry_steel_meeting_report.md`](./20261021_carry_steel_meeting_report.md)）
     - **結構化重點與數據資料庫**：鋼板月採購約 500 噸（44W/50W/Cat 4）、中鋼包裝防鏽與吊牌爐號溯源高度評價、海外進口占比三階段劇變（100% → 30% → 80%~90%）、服務中心創 6~7 年最強連續三個月業績、加工排程滿至明年 2~3 月、變電站工程（8"~12" 厚壁 HSS 方管）、油砂專案（Suncor/Syncrude）非北美鋼材第三方獨立測試規範與禁用中國鋼材規定、全加碼頭 40 天海關監管保稅策略與西岸至愛德蒙頓卡車運費（CAD $3,500/車 ≈ 6¢/lb）。
  2. **[`20261021_1121_02_carry_steel_audio_report.md`](./20261021_1121_carry_steel/20261021_1121_02_carry_steel_audio_report.md)**（同根目錄 [`carry_steel_20261021_audio_report.md`](./carry_steel_20261021_audio_report.md)）
     - **完整音訊解析報告**：包含執行摘要與全部 24 段（`00:00:00` – `01:09:55`）時間軸詳細紀錄。
  3. **[`20261021_1121_03_carry_steel_raw_notes.md`](./20261021_1121_carry_steel/20261021_1121_03_carry_steel_raw_notes.md)**（同根目錄 [`20261021_carry_steel_raw_notes.md`](./20261021_carry_steel_raw_notes.md)）
     - **未刪減分段聽覺完整底稿**：完整保留 24 段對話、英文原句引述（Quotes）、中鋼內部中文討論與量化數據細節。
  4. **原生 Word 檔案（`.docx`）**：
     - [`20261021_1121_Carry_Steel_Meeting_Report.docx`](./20261021_1121_carry_steel/20261021_1121_Carry_Steel_Meeting_Report.docx)
     - [`20261021_1121_Carry_Steel_Audio_Report.docx`](./20261021_1121_carry_steel/20261021_1121_Carry_Steel_Audio_Report.docx)
     - [`20261021_1121_Carry_Steel_Raw_Notes.docx`](./20261021_1121_carry_steel/20261021_1121_Carry_Steel_Raw_Notes.docx)

---

## 📁 場次 05：Russel Metals（2026-10-21 14:42 – 15:54 MDT）

### 1. 檔案清單與用途說明
- **時間序歸檔目錄 [`20261021_1442_russel_steel/`](./20261021_1442_russel_steel/)**（亦同步保留於根目錄 `./`）：
  1. **[`20261021_1442_01_russel_steel_meeting_report.md`](./20261021_1442_russel_steel/20261021_1442_01_russel_steel_meeting_report.md)**（同根目錄 [`20261021_russel_steel_meeting_report.md`](./20261021_russel_steel_meeting_report.md)）
     - **結構化重點與數據資料庫**：全加拿大第一大碳鋼分銷龍頭（北美第 5 大）Edmonton 廠 24/7 全天候生產；中鋼 1 月釋出 500 噸鋼板配額（Russel 優先）；中鋼專用碼頭直裝散貨船方案突破陸運 48 呎限制（供應 60'~68' 超長 50/80 Cat 3 橋梁板並與 A516 壓力容器板拼單）；詢價農機專用薄耐磨板 AR200/AR225（700噸/年），嚴格要求高光烤漆表面並排除 Steckel Mill（橘皮缺陷）；解套 API 650 Class 3 MTR 備註機制；揭露加西三區採購比例（BC 90% 進口、AB 60% 進口、Winnipeg 90% 國產）及 Russel 對國產鋼廠漲價限額之強硬反制（警告進口 5 個月交期反噬）。
  2. **[`20261021_1442_02_russel_steel_audio_report.md`](./20261021_1442_russel_steel/20261021_1442_02_russel_steel_audio_report.md)**（同根目錄 [`russel_steel_20261021_audio_report.md`](./russel_steel_20261021_audio_report.md)）
     - **完整音訊解析報告**：包含執行摘要與全部 25 段（`00:00:00` – `01:12:28`）時間軸詳細紀錄（記錄 Steve 離席與中場休息交換意見細節）。
  3. **[`20261021_1442_03_russel_steel_raw_notes.md`](./20261021_1442_russel_steel/20261021_1442_03_russel_steel_raw_notes.md)**（同根目錄 [`20261021_russel_steel_raw_notes.md`](./20261021_russel_steel_raw_notes.md)）
     - **未刪減分段聽覺完整底稿**：完整保留 25 段對話、英文原句引述（Quotes）、中鋼內部中文討論與量化數據細節。
  4. **原生 Word 檔案（`.docx`）**：
     - [`20261021_1442_Russel_Steel_Meeting_Report.docx`](./20261021_1442_russel_steel/20261021_1442_Russel_Steel_Meeting_Report.docx)
     - [`20261021_1442_Russel_Steel_Audio_Report.docx`](./20261021_1442_russel_steel/20261021_1442_Russel_Steel_Audio_Report.docx)
     - [`20261021_1442_Russel_Steel_Raw_Notes.docx`](./20261021_1442_russel_steel/20261021_1442_Russel_Steel_Raw_Notes.docx)



---

## 📁 場次 06：Varsteel Ltd.（2026-10-22 14:04 – 15:56 MDT）

### 1. 檔案清單與用途說明
- **時間序歸檔目錄 [`20261022_1404_varsteel/`](./20261022_1404_varsteel/)**（亦同步保留於根目錄 `./`）：
  1. **[`20261022_1404_01_varsteel_meeting_report.md`](./20261022_1404_varsteel/20261022_1404_01_varsteel_meeting_report.md)**（同根目錄 [`20261022_1404_01_varsteel_meeting_report.md`](./20261022_1404_01_varsteel_meeting_report.md)）
     - **結構化重點與數據資料庫**：全加美西 37 處服務中心網絡（收購 Transbec 魁北克 5 廠）；現場發掘年需求約 3,000 噸 AR400F/AR450F/A514 調質耐磨板重大新商機且**完全豁免加拿大反傾銷稅**；剖析痛失 5,000 噸 12mm 熱軋厚捲原因（中鋼 26 噸帶鋼超過 Delta 廠 22.5~25 噸天車極限且 Saga 拒載），提出入爐前「鋼胚對半鋸切（切為 13 噸鋼胚）」之根本破局方案；600 噸 350WT Cat 3 橋梁板在詢案證實中鋼厚板長度極限達 18.5 公尺（打破 40 呎限制）且 120" 超寬板排他性優勢顯著；單一 MTR 整合 API 650 Group 3（對標現代製鐵）；揭示北美 AI 超大規模資料中心建設狂潮引爆重型型鋼與剪切厚板大缺貨；雙方商定建立每月 3,000~5,000 噸常態月度訂購計畫。
  2. **[`20261022_1404_02_varsteel_audio_report.md`](./20261022_1404_varsteel/20261022_1404_02_varsteel_audio_report.md)**（同根目錄 [`20261022_1404_02_varsteel_audio_report.md`](./20261022_1404_02_varsteel_audio_report.md)）
     - **完整音訊深度解析報告**：包含執行摘要與全部 38 段（`00:00:00` – `01:51:53`）時間軸詳細紀錄（涵蓋 2 英吋重型冷整平機 1/2 A6 平坦度、加拿大三本土廠危機、溫哥華港 Lynnterm 鋼捲 3×3 打帶工安等）。
  3. **[`20261022_1404_03_varsteel_raw_notes.md`](./20261022_1404_varsteel/20261022_1404_03_varsteel_raw_notes.md)**（同根目錄 [`20261022_1404_03_varsteel_raw_notes.md`](./20261022_1404_03_varsteel_raw_notes.md)）
     - **未刪減分段聽覺完整底稿**：完整保留 38 段對話、英文原句引述（Quotes）、中鋼內部中文研商與量化數據細節。
  4. **原生 Word 檔案（`.docx`）**：
     - [`20261022_1404_Varsteel_Meeting_Report.docx`](./20261022_1404_varsteel/20261022_1404_Varsteel_Meeting_Report.docx)
     - [`20261022_1404_Varsteel_Audio_Report.docx`](./20261022_1404_varsteel/20261022_1404_Varsteel_Audio_Report.docx)
     - [`20261022_1404_Varsteel_Raw_Notes.docx`](./20261022_1404_varsteel/20261022_1404_Varsteel_Raw_Notes.docx)
