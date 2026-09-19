# AI Literature Organizer｜文獻整理器

AI Literature Organizer 是 Windows 桌面程式，可讀取 PDF 文字，使用 Google Gemini 依研究者自訂的分類與標籤整理文獻，並建立 Excel 索引。它會保留原始 PDF 備份、產生整理版 PDF，並記錄重複與處理失敗的檔案。

## 下載

從 [最新版本](https://github.com/mercury12100/literature-organizer-releases/releases/latest) 下載 Windows 安裝程式。1.3.1 版改善了分類與小標籤建議、中文分類說明，以及頁籤名稱。

## 快速開始

1. 取得 [Google AI Studio API Key](https://aistudio.google.com/apikey)。
2. 在「分類與標籤」建立研究模板，可選代表文獻讓 AI 提出更多細部標籤及新主要分類，審核後儲存。
3. 在「批次整理」輸入 API Key、選擇模型、PDF 來源及輸出資料夾，按「開始整理」。
4. 在「文獻索引」搜尋文獻；到輸出資料夾查看 Excel、整理版 PDF 和原始備份。

完整安裝說明、操作步驟、輸出檔案與更新方式請閱讀 [應用程式介紹與操作流程](APP_GUIDE.md)。

> PDF 擷取的文字會傳送至 Gemini 分析。請先確認文獻內容適合傳送到該服務，並依自己的 Google 帳戶設定留意 API 用量與費用。