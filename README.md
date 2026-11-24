# CPG 病理推理 / CPG Pathophysiology Reasoning

把 Ambulance Victoria CPG 每個主題背後的病理生理機轉拆出來，用病例、模擬、討論與作業練習到院前臨床推理，並附台灣 EMT-1／EMT-2／EMT-P 執行範圍標註與臨床指導員指南。

An interactive site that breaks each Ambulance Victoria CPG topic down to its pathophysiology and teaches prehospital clinical reasoning through cases, simulations, discussion and assignments, with Taiwanese EMT scope-of-practice notes and a guide for clinical instructors.

- 中文版：`index.html`
- English version: `en/index.html`

兩個版本都是單一 HTML 檔，不需要建置或伺服器端程式。
Both versions are single self-contained HTML files; no build step or server code is needed.

## 部署到 GitHub Pages

1. 把這個資料夾的所有檔案（含 `.nojekyll` 和 `en/`）放進 repo 根目錄。
2. GitHub repo → Settings → Pages → Build and deployment：Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`。
3. 幾分鐘後網址會是 `https://<帳號>.github.io/<repo 名稱>/`，英文版在 `/en/`。

## 說明

- 學習進度、測驗紀錄與研讀整理只存在使用者自己的瀏覽器（localStorage），中英文版共用同一份紀錄。
- 本網站為教學用途，自行整理臨床指引背後的病理生理概念，未重製 Ambulance Victoria CPG 的內容與流程圖。指引主題參考 Ambulance Victoria Clinical Practice Guidelines（CC BY-NC-ND 4.0）。藥物劑量、適應症與執行層級，請依最新版指引及所屬機關規範。
- This site is for education only. It summarises the pathophysiology behind the guidelines and does not reproduce Ambulance Victoria CPG content or flowcharts. Follow current guidelines and your service's rules for doses, indications and scope of practice.

國立臺北護理健康大學 健康科技學院 · 張育通
