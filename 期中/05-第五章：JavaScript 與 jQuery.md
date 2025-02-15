第五章：JavaScript 與 jQuery

# JavaScript 的基礎知識與語法
## JavaScript 是一種用於網頁前端開發的程式語言，它可以使網頁更具交互性，動態性和功能性。以下是 JavaScript 的一些基礎知識和語法：
### 變數
#### 在 JavaScript 中，可以使用關鍵字 var、let 或 const 宣告變數。其中，var 是舊版的宣告方式，而 let 和 const 是 ES6 引入的新宣告方式。變數可以存儲任何類型的值，包括數字、字串、布林值、對象、陣列等等。

### 函數
#### 在 JavaScript 中，可以使用 function 關鍵字定義函數。函數是一段可以重複使用的代碼塊，可以將一段程式碼封裝在函數內，並在需要的時候呼叫它。在定義函數時，可以定義參數，並在呼叫函數時傳遞值給參數。

### 條件語句
#### 在 JavaScript 中，可以使用 if、else if 和 else 關鍵字定義條件語句。條件語句根據一個或多個條件來執行不同的代碼塊。如果條件成立，就執行 if 語句；如果條件不成立，就執行 else 語句。

### 迴圈
#### 在 JavaScript 中，可以使用 for、while 和 do-while 關鍵字定義迴圈。迴圈是一種可以重複執行一段代碼的結構，可以在一個範圍內重複執行一個代碼塊，直到滿足特定條件時停止。

### 事件
#### 在 JavaScript 中，可以使用事件來處理用戶的交互行為。事件是指網頁中發生的任何動作，例如單擊、滑鼠移動、鍵盤輸入等等。可以使用 addEventListener() 方法綁定事件，並在事件觸發時執行相應的代碼。

### 對象
#### 在 JavaScript 中，對象是一種由屬性和方法組成的結構。可以使用 {} 花括號定義對象，並在其中定義屬性和方法。屬性是對象的特徵或特性，方法是對象可以執行的操作。

### 陣列
#### 在 JavaScript 中，陣列是一種用於存儲多個值的結構。可以使用 [] 方括

# 常用的 JavaScript 函數和方法介紹
## 以下是常用的 JavaScript 函數和方法介紹：
### alert() 方法會彈出一個包含文本的對話框，用於向用戶顯示一些信息。
### console.log() 方法用於將信息輸出到控制台，通常用於調試和測試 JavaScript 代碼。
### prompt() 方法會彈出一個包含輸入框的對話框，用於讓用戶輸入一些信息。
### parseInt() 方法用於將字符串轉換為整數，parseFloat() 方法用於將字符串轉換為浮點數。
### String() 方法用於將值轉換為字符串，Number() 方法用於將值轉換為數字。
### Math 是 JavaScript 內置對象，包含一些常用的數學方法和常量。
### slice() 和 substring() 方法用於截取字符串中的一部分。
### indexOf() 和 lastIndexOf() 方法用於查找字符串中指定子串的位置。
## 以上是一些常用的 JavaScript 函數和方法，它們可以使開發人員更有效地編寫 JavaScript 代碼。

# jQuery 的基礎知識與使用方法
## jQuery 是一種輕量級的 JavaScript 函式庫，可以簡化 JavaScript 在網頁上的開發。以下是 jQuery 的基礎知識與使用方法：
### 下載 jQuery
#### 可以在 jQuery 官方網站上下載 jQuery，或者使用 CDN（Content Delivery Network） 來加速載入。
### 選擇元素
#### 使用 jQuery 的 $() 函式來選擇元素，就像 CSS 的選擇器一樣。
### 操作元素
#### 使用 jQuery 可以輕鬆地操作元素的屬性、樣式、內容等。
### 鏈式語法
#### jQuery 支持鏈式語法，這意味著可以將多個操作連接起來，並使用一個 $() 函式來選擇元素。
# 常用的 jQuery 函數和方法介紹
## 以下是一些常用的 jQuery 函數和方法介紹：

### 選擇元素
$()：選擇元素。可以使用 CSS 選擇器、ID、類名等。
find()：查找子元素。
parent()：查找父元素。
siblings()：查找兄弟元素。
next()：查找下一個元素。
prev()：查找前一個元素。

### 操作元素
text()：獲取或設置元素的文字內容。
html()：獲取或設置元素的 HTML 內容。
val()：獲取或設置表單元素的值。
attr()：獲取或設置元素的屬性。
addClass()：為元素添加類名。
removeClass()：從元素中刪除類名。
toggle()：切換元素的可見性。
fadeIn()：淡入元素。
fadeOut()：淡出元素。
slideUp()：向上滑動元素。
slideDown()：向下滑動元素。
animate()：以動畫方式更改元素的樣式或屬性。
### 事件處理
click()：點擊事件。
hover()：鼠標懸停事件。
focus()：焦點事件。
blur()：失去焦點事件。
submit()：提交事件。
keydown()：按下按鍵事件。
keyup()：鬆開按鍵事件。
resize()：調整大小事件。
### AJAX
$.ajax()：執行 AJAX 請求。
$.get()：使用 GET 方法執行 AJAX 請求。
$.post()：使用 POST 方法執行 AJAX 請求。
$.getJSON()：使用 JSON 格式獲取數據。
## 這些只是 jQuery 中一小部分常用的函數和方法，還有很多其他的函數和方法可供使用。需要根據實際情況進行選擇和使用。
