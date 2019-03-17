# Html 語法基礎說明
***
> &lt;!DOCTYPE html&gt;  定義文件為HTML5
>
> &lt;html&gt;  敘述該元件是一個HTML頁面的根元素
>
>  &lt;head&gt;  敘述該元素包含有關文檔的元信息
>
>  &lt;title&gt;  敘述該元素指定該文檔的標題
>
>  &lt;body&gt;  敘述該元素包含可見的頁面內容
>
>  HTML標題使用 &lt;H1&gt;  到 &lt;H6&gt;  \* (Heading) \* 標籤定義 ***由大到小***
>  &lt;h1&gt;  等於24px \*(pixel)\*
>     
>  &lt;h1&gt; This is heading used 24px&lt;/h1&gt; 
>
>  &lt;h2&gt;  等於22px \*(pixel)\*      
>
>  &lt;h2&gt; This is heading used 22px&lt;/h2&gt; 
>
>  &lt;h3&gt;  等於18px \*(pixel)\*      
>
>  &lt;h3&gt; This is heading used 18px&lt;/h3&gt; 
>
>  &lt;h4&gt;  等於16px \*(pixel)\*      
>
>  &lt;h4&gt; This is heading used 16px&lt;/h4&gt;
> 
>  &lt;h5&gt;  等於12px \*(pixel)\*     
>
>  &lt;h5&gt; This is heading used 12px&lt;/h5&gt;
> 
>  &lt;h6&gt;  等於10px \*(pixel)\*
>
>  &lt;h6&gt; This is heading used 10px&lt;/h6&gt; 
> 
>  HTML段落使用 &lt;p&gt; \*(paragraph)\* 標籤定義
>
>  新增顏色屬性 \*(color)\*
>
>  &lt;p style="color:red"&gt; Red text&lt;/p&gt;  or &lt;p style="color:#FF0000"&gt; Red text&lt;/p&gt;  or &lt;p style="color:rgb(255,0,0)"&gt; Red text&lt;/p&gt;  or &lt;p style="color:rgba(255,0,0,1)"&gt; Red text&lt;/p&gt;
> 
>  新增標題文字 \*(title)\*
>
>  &lt;p title="指我會冒出來"&gt; This is a paragraph.&lt;/p&gt; 
>
>  改變文字對齊 \*(text-aligh)\* 樣式 \*(style)\* ***置左 left , 置中 center , 置右 right***
>
>  &lt;p style="text-align:left;"&gt; Left paragraph.&lt;/p&gt; 
>
>  &lt;p style="text-align:center;"&gt; Center paragraph.&lt;/p&gt;
> 
>  &lt;p style="text-align:right;"&gt; Right paragraph.&lt;/p&gt; 
>
>  改變文字字體 \*(font-family)\* 樣式 \*(style)\* ***其他字體需要可自行上網查詢***
>
>  &lt;p style="font-family:courier;"&gt; This is a paragraph.&lt;/p&gt; 
>  
>  HTML格式化文本使用&lt;pre&gt; 標籤定義
> 
>  HTML文字使用&lt;a&gt; 標籤定義
>
>  新增超連結屬性 \*(herf)\*
> 
>  &lt;a href="連結網址"&gt; This is a link&lt;/a&gt;  or &lt;a href='連結網址'&gt; This is a link&lt;/a&gt; 
>
>  改變文字大小 \*(font-size)\* 樣式 \*(Style)\*
>
>  &lt;a style="font-size:60px"&gt;  or &lt;a style="font-size:2.5rem"&gt; 
>
>  新增背景顏色 \*(color)\* 樣式 \*(style)\*
>
>  &lt;a style="background-color:DodgerBlue;"&gt;  
> 
>  HTML圖片使用&lt;img&gt; \*(image)\* 標籤定義
>
>  新增代替本文屬性 \*(alt)\* 與長 \*(height)\* 寬 \*(width)\* 屬性
>
>  &lt;img src="圖片網址" alt="文字代替圖片" width="100" height="200"&gt;  or &lt;img src='圖片網址' alt='文字代替圖片' width='100' height='200'&gt; 
>
>  HTML按鈕使用&lt;button&gt; 標籤定義
>
>  新增禁用屬性 \*(disabled)\*
>
>  &lt;button disabled&gt; 按鈕文字&lt;/button&gt;  
> 
>  HTML列表使用&lt;ul&gt;  （無序/項目符號列表）或&lt;ol&gt; （有序/編號列表）標記定義，後跟&lt;li&gt;  標記（列表項）
>
>  &lt;ul&gt;                              &lt;ol&gt; 
>
>       &lt;li&gt; 文字一&lt;/Li&gt;                   &lt;li&gt; 文字一&lt;/Li&gt; 
>
>       &lt;Li&gt; 文字二&lt;/Li&gt;       or          &lt;Li&gt; 文字二&lt;/Li&gt;
> 
>       &lt;Li&gt; 文字三&lt;/Li&gt;                   &lt;Li&gt; 文字三&lt;/Li&gt; 
>
>  &lt;/ul&gt;                             &lt;/ol&gt; 
> 
>  HTML換行使用&lt;br&gt; 標籤定義
> 
>  HTML水平線使用&lt;hr&gt; \*(Horizontal)\* 標籤定義
> 
>  HTML粗體使用&lt;b&gt; \*(Bold)\* 標籤定義
> 
>  HTML重要文字使用&lt;strong&gt; 標籤定義 \*效果跟&lt;b&gt; 標籤效果差不多\*
> 
>  HTML斜體文字使用&lt;i&gt; \*(Italic)\* 標籤定義
> 
>  HTML強調文字使用&lt;em&gt; 標籤定義 \*效果跟&lt;i&gt; 標籤效果差不多\*
> 
>  HTML標記文字使用&lt;mark&gt; 標籤定義
> 
>  HTML刪除文字使用&lt;del&gt; 標籤定義
> 
>  HTML插入文字使用&lt;ins&gt; 標籤定義 \*(baseline)\*
> 
>  HTML下標文字使用&lt;sub&gt; 標籤定義
> 
>  HTML上標文字使用&lt;sup&gt; 標籤定義
> 
>  HTML縮小文字使用&lt;small&gt; 標籤定義
> 
>  HTML短引號使用&lt;q&gt; 標籤定義
>
>  &lt;q&gt; 123&lt;/q&gt;  or 直接輸入 "123" \*(個人推薦直接使用雙引號)\*
> 
>  HTML引用使用&lt;blockquote&gt; 標籤定義
>
>  &lt;blockquote city="引用網址"&gt; 引用文字&lt;/blockquote&gt; 
> 
>  HTML地址使用&lt;address&gt; 標籤定義，元件通常顯示斜體
>
>  個人不太使用此標籤，如果要達到斜體效果通常使用
>
>  &lt;i&gt; 標籤 or &lt;a style="font-style:italic"&gt; 文字&lt;/a&gt; 
> 
> 圖片位址 https://www.image-map.net/