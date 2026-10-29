# 小小視唱室

兒童視唱練習單產生器。純靜態 HTML、CSS、JavaScript，無收音、無播放功能。

- 自訂音域、大小調、拍號與最短音符
- 附點、休止符開關
- 每題 4 或 8 小節，批次生成 1–24 題，單題重新生成
- A4 PDF，開啟、下載及支援時使用系統分享
- 響應式手機版；樂譜區可水平捲動

## GitHub Pages

檔案放在儲存庫根目錄。Settings → Pages → Deploy from a branch → main → /(root) → Save。

## 驗證

生成器已通過 8,448 組拍數、音域、時值、音程與結尾音測試。
桌面瀏覽器已測試 PDF 生成；390px 版面已檢查。iPhone Safari 實機下載尚待驗證。

## 第三方套件

- abcjs 6.4.4（MIT）
- jsPDF 2.5.2（MIT）

套件授權標頭保留於 vendor 檔案。標題字型使用 Google Fonts Noto Serif TC，未載入時使用系統字型。
