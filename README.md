# AI Literature Organizer｜文獻整理器

AI Literature Organizer 是 Windows 桌面程式，可讀取 PDF 文字，使用 Google Gemini 依研究者自訂的分類與標籤整理文獻，並建立 Excel 索引。它會保留原始 PDF 備份、產生整理版 PDF，並記錄重複與處理失敗的檔案。

## 快速開始

1. 從 [Releases](https://github.com/mercury12100/literature-organizer-releases/releases/latest) 下載最新版 Windows 安裝程式；若尚未提供安裝檔，請依完整指南從原始碼啟動。
2. 取得 [Google AI Studio API Key](https://aistudio.google.com/apikey)。
3. 在「02 分類與標籤」建立研究模板，設定主要分類與標籤。
4. 在「01 批次整理」輸入 API Key、選擇模型、PDF 來源及輸出資料夾，按「開始整理」。
5. 在「03 文獻索引」搜尋文獻；到輸出資料夾查看 Excel、整理版 PDF 和原始備份。

完整安裝說明、操作步驟、輸出檔案與更新方式請閱讀 [應用程式介紹與操作流程](APP_GUIDE.md)。

> PDF 擷取的文字會傳送至 Gemini 分析。請先確認文獻內容適合傳送到該服務，並依自己的 Google 帳戶設定留意 API 用量與費用。