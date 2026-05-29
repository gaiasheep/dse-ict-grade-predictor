# 📊 DSE ICT Grade Predictor (預估成績計算器)

![GitHub Unified Grade](https://img.shields.io/badge/Updated-2026-blue?style=for-the-badge)
![Powered by](https://img.shields.io/badge/Powered%20by-Claude%20AI-violet?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-TC%20%7C%20SC%20%7C%20EN-emerald?style=for-the-badge)

一個專為香港 DSE ICT（資訊及通訊科技科）師生打造的**專業級、多功能成績預估評估工具**。完美適應學校日常模擬考（Mock）及階段測驗的多變滿分需求，並基於最新考情與實考數據提供即時視覺化回饋。

🌐 **Live Demo (線上體驗):** `https://你的github用戶名.github.io/dse-ict-grade-predictor/` *(請替換為你的 GitHub Pages 鏈接)*

---

## ✨ 核心亮點 (Key Features)

* **🌍 完美三語支持 (i18n):** 支援**繁體中文、簡體中文、英文**無縫切換，一鍵適應不同應考語言（EMI/CMI）學生的需求。
* **🛠️ 彈性滿分設定 (Mock-friendly):** 擺脫傳統計算器寫死滿分的限制！Paper 1 及 Paper 2 各單元均採用「得分 / 滿分」雙輸入設計，完美兼容各校校內 Mock 卷、Term Exam 的自定義滿分。
* **🔒 嚴格選修「三選二」鎖定:** 完美契合 HKEAA 最新考情。即時監聽 2A（數據庫）、2B（網絡）、2C（算法與編程）輸入狀態，一旦填妥任意兩科，自動變灰鎖定第三科，杜絕錯誤輸入。
* **📈 2025 實考 Cut-off 精準預測:** 等級判定邊界（Level 3 至 5\*\*）嚴格對標 **2025 DSE ICT 真實 Estimated Cut-Off 分數線**（如 89% 獲 5\*\*，85% 獲 5\*），拒絕盲目估分。
* **🧩 SBA 智能分流估算:** 針對中五/中六不同教學進度，支持同時輸入 Task 1 (25M) 与 Task 2 (15M)；若 SBA 完全留空，系統自動切換為純筆試等比例放大模式。
* **⚡ 實時零延遲計算:** 全網頁監聽 `oninput` 異步更新，進度條流暢動畫過渡，拒絕原生彈窗 `alert()`，帶來極佳的用戶體驗。

---

## 📐 計分比重架構 (Weighting & Formula)

本計算器嚴格遵循香港考評局（HKEAA）官方比重：

| 評核部分 (Component) | 官方佔比 (Weighting) | 網頁內置預設滿分 (Default Full Mark) |
| :--- | :---: | :--- |
| **Paper 1 (必修部分)** | **55%** | Paper 1A: 40M \| Paper 1B: 60M |
| **Paper 2 (選修部分)** | **25%** | 任選兩科作答，每科 30M (總滿分 60M) |
| **SBA (校本評核)** | **20%** | Task 1: 25M (固定) \| Task 2: 15M (固定) |

---

## 🚀 部署與使用方法 (Deployment)

本項目為純前端單文件架構（Single HTML File），無需任何後端服務器或數據庫配置：

1. **本地使用：** 下載 `index.html`，雙擊即可在任意瀏覽器中運行。
2. **GitHub Pages 免費託管：**
   - 將代碼上傳至你的 GitHub 倉庫。
   - 進入倉庫的 `Settings` -> `Pages`。
   - 在 **Build and deployment** 下選擇 `Deploy from a branch`，並將 Branch 設為 `main` (或 `master`)，點擊 Save。
   - 幾分鐘後即可獲得全港公開的訪問網址！

---

## 📝 免責聲明 (Disclaimer)

* 此測試結果基於過往數據與 2025 估計切線進行推算，預估等級僅供同學複習與備考參考。真實成績以香港考評局（HKEAA）當季發放的成績通知單為準。

---

## 👨‍💻 作者與致謝 (Author & Credits)

* **Crafted with 💻 and ❤️ by Gaia Yang** * 📩 **Get in touch:** [gaiayang.edu@gmail.com](mailto:gaiayang.edu@gmail.com)
* **Powered by:** 🤖 Claude AI & 🐙 GitHub
