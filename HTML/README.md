# HTML基礎語法
|    HTML   |      中文     |
|-----------|:-------------|
|\<\!DOCTYPE html\>| 定義文件為HTML5 |
|\<html\>|敘述該元件是一個HTML頁面的根元素|
|\<head\>|敘述該元素包含有關文檔的元信息|
|\<title\>|敘述該元素指定該文檔的標題|
|\<body\>|敘述該元素包含可見的頁面內容|
|\<h1\>|標題(Heading)，大小為24px|
|\<h2\>|標題(Heading)，大小為22px|
|\<h3\>|標題(Heading)，大小為18px|
|\<h4\>|標題(Heading)，大小為16px|
|\<h5\>|標題(Heading)，大小為12px|
|\<h6\>|標題(Heading)，大小為10px|
|\<p\>|段落(paragraph)|
|\<a\>|文字|
|\<img\>>|圖片(image)，屬性 src="圖片網址"、alt="文字代替圖片"|
|\<button\>|按鈕|
|\<ul\>|無序/項目符號列表，後跟\<li\> 標記（列表項）|
|\<ol\>|有序/編號列表，後跟\<li\> 標記（列表項）|
|\<dl\>|描述列表，後跟\<dt\>標記定義了術語（名稱），或後跟\<dd\> 標記描述各術語|
|\<br\>|換行|
|\<hr\>|水平線(Horizontal)|
|\<b\>|粗體 (Bold) |
|\<strong\>|重要文字，效果跟\<b\> 標籤效果差不，|
|\<i\>|斜體(Italic)|
|\<em\>|強調文字，效果跟\<i\> 標籤效果差不，|
|\<mark\>|標記文字，效果跟style='backgroun-color:yelllow'差不多|
|\<del\>|刪除文字|
|\<ins\>|插入文字|
|\<sub\>|下標文字|
|\<sup\>|上標文字|
|\<small\>|縮小文字|
|\<q\>|短引號，效果\<q\>123\</q\> 等於 "123" (個人推薦直接使用雙引號)|
|\<blockquote\>|引用文章，屬性city="引用網址"|
|\<address\>|地址，元件通常顯示斜體個人不太使用此標籤，如果要達到斜體效果通常使用\<i\> 標籤 or \<a style="font-style:italic"\> 文字\</a\>|
|\<table\>|表格，每個表行都使用\<tr\/\>標記定義。使用\<th\/>標記定義表頭。默認情況下，表格標題為粗體且居中。使用\<td\/\>標籤定義表數據/單元 。|
|\<thead\>|表格開頭 ***tip 表格開頭如果需要粗體通常使用 \<th\/\>標籤而不是\<tr\/\>***|
|\<tbody\>|表格身體|
|\<tfoot\>|表格頁角|
|\<div\>|區塊|
|\<span\>|裡面的元素 ***tips 可以想像成元件裡的小區塊***|
|\<iframe\>|於在網頁中顯示網頁，屬性src="URL"。|
|\<from\>|表單，屬性action="url"|
|\<input\>|表單元素，屬性type[可點選此](http://www.w3school.com.cn/tags/att_input_type.asp)或是往下查詢屬性。|
|\<select\>|下拉是選單，後跟 \<option\>，屬性size ***(顯示筆數)*** 、 multiple ***(多選)***|
|\<textarea\>|多行文字，屬性rows ***(顯示行數)***、cols ***(每列字數)***|
|\<datalist\>|數據列表，必須預先定義的選項的列表\<input\>元素，在list該屬性\<input\>元素，必須參照 id該屬性\<datalist\>的元素。[點我看範例](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_elem_datalist)|
|\<output\>|表示計算的結果 [點我看範例](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_elem_output)|
|\<canvas\>|畫布|
|\<video\>|影片，後跟 \<source src="影片" type="副檔名"\>|
|\<audio\>|音效，後跟 \<source src="音樂" type="副檔名"\>|
|\<abbr\>|首字母縮略詞。 ***tip 通常會使用title屬性與border來實現***|
|\<article\>|獨立內容。 ***tip 通常會用/<div/>取代***|
|\<code\>|短語標記。 ***tip 如想顯示程式碼可以用此標籤***|
|\<details\>|指定用戶可以按需查看或隱藏的其他詳細信息。|
|\<map\>|定義客戶端圖像映射。圖像映射是具有可點擊區域的圖像。[點我查看範例](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_areamap)；[線上工具](https://www.image-map.net/)|
|\<meter\>|量規。|
|\<progress\>|任務的進度。|
|\<nav\>|上方導覽列。|





# HTML屬性概述
|屬性|中文|值|
|-----------|:-------------|:-------------|
|id|定義標籤姓名(不可重複)|text|
|class|定義標籤姓名(可重複)|text|
|width|寬度|px %(百分比) ... ***ex width:100%***|
|height|長度|px %(百分比) ... ***ex height:100%***|
|float|浮動|right(置右)、left(置左) ***ex float:left***|
|colspan|列合併，用於\<th\>、\<td\>標籤| ***ex colspan="2" 合併兩列***|
|rowspan|行合併，用於\<th\>、\<td\>標籤| ***ex rowspan="2" 合併兩行***|
|type|定義列表項標記的類型|1 ***(從1開始以數列排序)*** 、A ***(從A開始以英文大寫字母排序)*** 、a***(從a開始以英文小寫字母排序)*** 、I ***(從大寫羅馬字母排序)*** 、i ***(從小寫羅馬字母排序)***|
|start|指定的數字開始計數，用於\<ol\>標籤。| ***ex start="50" 從50開始***|
|type|宣告表單元素，用於\<input\>標籤。 |button ***(一般按鈕)*** 、 submit ***(提交按鈕)*** 、image ***(圖片提交按鈕，需多加src屬性)*** 、 text ***(輸入文字)*** 、password ***(輸入密碼)*** 、checkbox ***(複選框)*** 、 radio ***(單選框)*** 、 file ***(文件上傳)*** 、 hidden ***(隱藏輸入，多用漁傳值)*** 、 reset ***(重置按鈕)*** 、 range ***(範圍)*** 、 date ***(日期)*** 、 time ***(時間)*** 、 [查看更多](https://www.w3schools.com/html/html_form_input_types.asp)|
|name|宣告表單元素名稱，用於\<input\>標籤。 ***(tip 後端接收大多是依據name來判斷值)***|string|
|value|宣告表單元素質，用於\<input\>標籤。 ***(tip 後端接收大多是依據name來接收value)***|string|
|placeholder|文字提示|string|
|target|開啟新頁面屬性。|_self ***(在當前窗口顯示，不冒出新頁面)*** 、_blank ***(在新窗口顯示，冒出新頁面)***|
|method|提交表單使用的HTTP方法。|GET or POST [淺談GET與POST](https://blog.toright.com/posts/1203/%E6%B7%BA%E8%AB%87-http-method%EF%BC%9A%E8%A1%A8%E5%96%AE%E4%B8%AD%E7%9A%84-get-%E8%88%87-post-%E6%9C%89%E4%BB%80%E9%BA%BC%E5%B7%AE%E5%88%A5%EF%BC%9F.html)|

# Style
|屬性|中文|值|
|-----------|:-------------|:-------------|
|padding|內間距|px rem ***ex padding:20px;***|
|text-align|文字對齊|left(置左)、center(置中)、right(置右)|
|list-style-type|列標標記樣式，用於\<ul\>標籤|disc ***(列標顯示 •)***、circle ***(列標顯示 。)*** 、square ***(列表顯示 ▪)*** 、none ***(無列表顯示))***|
|color|顏色|color name 、 rgb 、 rgba 、 hsl [色碼表](https://www.ifreesite.com/color/)|
|background-color|背景顏色|color name 、 rgb 、 rgba 、 hsl [色碼表](https://www.ifreesite.com/color/)|
|background-image|背景圖片|url("圖片位址/連結") ***ex background-image: url("picture.png")***|
|border|邊寬|邊寬寬度、邊寬樣式、邊寬顏色 ***ex border: 1px solid black;***|
|border-color|邊寬顏色|all or top right bottom left or top&bottom left&right ***ex border-color:blue; or border-color:blue yellow;*** |
|border-width|邊寬寬度|px rem ... ***ex border-width:3px;***|
|border-spacing|邊框間距|px rem ... ***ex border-spacing: 5px;***|
|border-style|邊寬樣式|solid、dotted... [其他更多](https://www.w3schools.com/css/css_border.asp)|
|border-collapse|標格邊框合併|separate(預設值)、collapse(單一邊框)、inherit(繼承自父層的 border-collapse 屬性值) ***key 通常使用border-style實現***|




