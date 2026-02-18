# Framework Duel | React vs Vue 對比工具

這是一個專為前端開發者設計的互動式比較工具，旨在透過視覺化介面與淺顯易懂的文字，幫助使用者快速了解 React 與 Vue 兩大主流框架的差異，並選擇最適合其專案的工具。

<br />

## 核心功能

- **響應式對比介面**：具備視覺層次的卡片設計，直觀對比特性、學習曲線與生態系。
- **深淺模式切換**：支援系統顏色偏好自動切換，並可手動選擇模式，狀態將持久化儲存於瀏覽器。
- **新手百科 (Accordion)**：針對 JSX、虛擬 DOM、響應式原理等專業術語，提供深入淺出的白話解釋。
- **技術規格表**：整理兩大框架的渲染機制、檔案大小及響應式原理等量化指標。
- **優化交互體驗**：包含平滑捲動回頂部、符合 16px 規範的易讀字體。

<br />

## 使用技術

- **核心技術**：HTML5, JavaScript (ES6+)
- **樣式處理**：[Tailwind CSS](https://tailwindcss.com/) (經由 CDN 載入)
- **代碼規範**：
  - [ESLint](https://eslint.org/) (遵循 Airbnb Base 規範)
  - [Prettier](https://prettier.io/) (代碼格式化)
- **開發輔助**：Gemini CLI

<br />

## 本地開發

若要在本地環境進行開發或檢查代碼規範，請遵循以下步驟：

1. **安裝依賴套件**：

   ```bash
   npm install
   ```

2. **執行 ESLint 檢查**：

   ```bash
   npm run lint
   ```

3. **自動修正代碼格式**：
   ```bash
   npm run lint:fix
   ```

<br />

## 專案部屬

本專案已成功部屬，您可以透過以下網址直接瀏覽：

- **預覽連結**：[https://2026-02-18-vibe-coding.vercel.app/](https://2026-02-18-vibe-coding.vercel.app/)

<br />

## 致謝

本專案由 **Gemini CLI** 協助開發，從介面設計、功能實作到代碼規範設定，皆由 AI 協作完成。

<br />

---

© 2026 Framework Duel.
