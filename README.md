# wuximidschoolengishExam
Develop by Gemini
📝 無錫中考英語作文通 (Wuxi English Essay Prep)

這是一個專為無錫中考（高中入學考試）英語作文設計的單頁面 Web 應用程式 (Single-Page Web App)。

它結合了 Google Gemini AI 技術，提供智能出題提示、即時作文批改、評分以及滿分範文生成功能。採用 iOS 風格設計，特別優化了移動端體驗，且所有程式碼整合在一個 .html 檔案中，無需安裝環境，即開即用。

✨ 主要功能

🤖 AI 智能批改：交卷後，AI 會根據中考標準進行 0-15 分評分，分析詞彙、語法、邏輯，並給出具體的改進建議。

✨ AI 範文生成：針對每一篇練習的題目，AI 會即時生成一篇高品質的滿分範文供學生對照學習。

🪄 智能出題助手：新增自定義題目時，輸入標題與要求，AI 可自動生成適合的「提示詞 (Hints)」。

⏱️ 模擬考場：內建 20 分鐘倒數計時器與實時字數統計（目標 80-100 字）。

📚 內建題庫 & 詞彙：包含近年無錫中考真題、無錫特色詞彙（如 Taihu Lake, Xiao Long Bao）及高分句型。

🛠️ 自定義題庫管理：使用者可自由新增、編輯或刪除題目，打造個人化練習庫。

📱 移動端優化：響應式設計，在手機上操作流暢，體驗接近原生 App。

🚀 快速開始

由於本專案採用零依賴 (Zero-Dependency) 架構，您不需要安裝 Node.js 或執行 npm install。

方法一：直接使用

下載本專案中的 WuxiEssayApp.html 檔案。

直接使用瀏覽器（Chrome, Safari, Edge 等）打開該檔案。

點擊首頁左上角的 設置 (⚙️) 圖標。

輸入您的 Google Gemini API Key 即可開始使用 AI 功能。

方法二：部署到靜態網站

您可以將 WuxiEssayApp.html 上傳到任何靜態網頁託管服務（如 GitHub Pages, Vercel, Netlify），甚至只需將其改名為 index.html 即可。

🔑 關於 API Key

本應用程式使用 Google Gemini API 進行 AI 運算。

您需要擁有自己的 Google AI Studio API Key。

安全性說明：您的 API Key 僅會儲存在您瀏覽器的 LocalStorage 中，不會上傳到任何第三方伺服器，請放心使用。

🛠️ 技術棧

本專案展示了如何在不使用打包工具（如 Webpack/Vite）的情況下構建現代 React 應用：

核心框架: React 18 & ReactDOM (透過 CDN 引入)

編譯器: Babel Standalone (用於瀏覽器端解析 JSX)

樣式庫: Tailwind CSS (透過 CDN 引入)

AI 模型: Google Gemini 1.5 Flash

圖標庫: 內建 SVG (無外部圖標字體依賴)

📸 截圖

(建議您在此處放幾張 App 的截圖，例如首頁、寫作介面、AI 批改結果頁面)

🤝 貢獻

歡迎提交 Pull Request 或 Issue！
由於這是一個單文件專案，請確保在修改時保持代碼結構的整潔。

📄 授權

本專案採用 MIT License 授權。
