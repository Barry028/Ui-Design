----- 請在上方下載課程範例檔及簡報 -----
# HTML、CSS 基礎課程
## 範例檔內含：
1. Javascript
2. 
3. 

&nbsp;

## 課程概要：
1. JS 的重點整理
2. 
3. 
4. 
5. 
6. 

&nbsp;

## 重點回顧：
* Javascript 為一**腳本語言**，它使你能夠動態的更新內容、控制多媒體、動畫……幾乎所有事。（好吧，不是所有事情，但神奇的是你可以通過短短幾行 JavaScript 程式碼實現。
* 副檔名為 **.js**

 * HTML 是一種標記語言，我們使用它組織網頁裡的內容並給予定義，例如：定義段落、標題、資料表格，或是在頁面嵌入圖片和影片。
 * CSS 是一種樣式規則的語言，用來幫我們的 HTML 內容上套用樣式，例如：設置背景顏色、字型，或讓內容以多欄的方式呈現。

* 基本結構：

    ```HTML
    <!--宣告文件格式-->
    <!DOCTYPE html>
    <!--語言-->
    <html lang="zh-Hans-TW">
    <!--通常放置網頁重要資訊-->
    <head>
        <!--編碼-->
        <meta charset="UTF-8">
        <title>Document</title>
    </head>
    <body>
    
    <!--顯示內容-->
    
    </body>
    </html>
    ```

### 獲取 DOM 元素有哪些方法
| 方法 | 描述 | 返回類型 |
| :-----| ----: | :----: |
| document.getElementById(id)            | 通過id獲取dom | 符合條件的dom對象|
| document.getElementsByTagName(tagName) | 通過標籤名獲取dom    | 符合條件的所有dom對象組成的類數組|
| document.getElementsByClassName(class) | 通過class獲取dom  | 符合條件的所有dom對象組成的類數組|
| document.getElementsByName(name)       | 通過標籤的屬性name獲取dom  | 符合條件的所有dom對象組成的類數組|
| document.querySelector(選擇器)          | 通過選擇器獲取dom  | 符合條件的第一個dom對象|
| document.querySelectorAll(選擇器)       | 通過選擇器獲取dom  | 符合條件的所有dom對象組成的類數組|



* 無結尾標籤 **Singleton tags** 會出現在樹狀模型的末端，也就是裡面**不會有內容**，常見的有：`<img>、<br>、<hr>、<link>等等`
* **相對路徑：** 從該文件位置出發到另一檔案的路徑
* **絕對路徑：** 透過 IP 到達的路徑
* HTML5 標籤增加了**語意化標籤、多媒體**
* 為了方便管理樣式，不太會將樣式寫在 style 屬性中
* **CSS(Cascading Style Sheets) 疊層樣式表**為一用來描述**樣式**的一份文件，透過**選擇器(selector)** 選取 HTML 結構上的元素做樣式的變化
* 一定要記得用 `<link rel="stylesheet" href="檔案路徑">` 將樣式加到 HTML 中
* 請善用**開發人員工具**作為除錯工具，對頁面按 右鍵 > 檢查！！
* 使用 **CSS 選擇器**原則：
    1. 若選擇器或樣式選取的元素相同，後寫的會蓋掉先寫的
    2. 多用**類別選擇器(.class)**
    3. 少用**元素選擇器(element)**，很容易有樣式重疊的問題
    4. 視情況使用 **id 選擇器(#id)**，同一頁面通常只會有一個，或留給其他語言操作的空間
    5. 注意**權重問題**：!important > style > #id > .class > element
        分數可註記為：0-0-0-0-0
    6. !important 有很高的權重，故要謹慎使用

### 外部資源參考：
-- 課程 --
* HTML 標籤 (W3C)：https://www.w3schools.com/tags/
* 無結尾標籤 Singleton：https://www.thoughtco.com/html-singleton-tags-3468620
* CSS 選擇器 (W3C)：https://www.w3schools.com/cssref/css_selectors.asp
* Emmet 快速鍵表：https://docs.emmet.io/cheat-sheet/
* 權重圖片說明：https://cssspecificity.com/

-- 設計靈感 --
* 色票靈感網站：http://colorhunt.co/
* Colors-canva's design：https://www.canva.com/colors/
* 設計師必讀的色彩心理學：https://buzzorange.com/techorange/2017/08/10/blue-is-most-important-color-for-ui-design/

-- Favicon製作 --
* realfavicongenerator：https://realfavicongenerator.net/

-- 討論文章 --
* 一般網頁容量大小：https://buzzorange.com/techorange/2017/08/10/blue-is-most-important-color-for-ui-design/
