## 
符合 W3C 標準的 HTML5 網頁，並使用原生 CSS 將卡片置中，成功印出 "Hello, World!"。
### 1. HTML5 標準結構
* `<!DOCTYPE html>`：宣告文件類型，強制瀏覽器使用最新的 HTML5 標準渲染網頁。
* `<meta charset="UTF-8">`：設定網頁字元編碼為 UTF-8，確保繁體中文、特殊符號能正常顯示不變成亂碼。
* `<meta name="viewport" content="width=device-width, initial-scale=1.0">`：響應式網頁（RWD）的靈魂，讓網頁寬度跟隨裝置螢幕寬度，縮放比例預設為 1，防止網頁在手機上縮小成螞蟻字。

### 2. 原生 CSS 置中技巧 (Flexbox)
在此範例中，使用了現代網頁最主流的排版工具 **Flexbox** 來達成完美的畫面正中央置中：
* `display: flex;`：將 `body` 變成彈性盒子（Flex Container）。
* `justify-content: center;`：讓裡面的內容在「水平方向」居中。
* `align-items: center;`：讓裡面的內容在「垂直方向」居中。
