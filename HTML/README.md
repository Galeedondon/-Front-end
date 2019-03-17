# Html 語法基礎說明
> <!DOCTYPE html> 定義文件為HTML5
> <html> 敘述該元件是一個HTML頁面的根元素
> <head> 敘述該元素包含有關文檔的元信息
> <title> 敘述該元素指定該文檔的標題
> <body> 敘述該元素包含可見的頁面內容
* * *
> HTML標題使用 <H1> 到 <H6> *Heading* 標籤定義 ***由大到小***
>> <h1> 等於24px*(pixel)*      
>> <h1>This is heading used 24px</h1>
>> <h2> 等於22px*(pixel)*      
>> <h2>This is heading used 22px</h2>
>> <h3> 等於18px*(pixel)*      
>> <h3>This is heading used 18px</h3>
>> <h4> 等於16px*(pixel)*      
>> <h4>This is heading used 16px</h4>
>> <h5> 等於12px*(pixel)*     
>> <h5>This is heading used 12px</h5>
>> <h6> 等於10px*(pixel)*
>> <h6>This is heading used 10px</h6>
>
> HTML段落使用 <p> *(paragraph)* 標籤定義
>> 新增顏色屬性*(color)*
>> <p style="color:red">Red text</p> or <p style="color:#FF0000">Red text</p> or <p style="color:rgb(255,0,0)">Red text</p> or <p style="color:rgba(255,0,0,1)">Red text</p>
>> 新增標題文字*(title)*
>> <p title="指我會冒出來">This is a paragraph.</p>
>> 改變文字對齊*(text-aligh)* 樣式*(style)* ***置左 left , 置中 center , 置右 right***
>> <p style="text-align:left;">Left paragraph.</p>
>> <p style="text-align:center;">Center paragraph.</p>
>> <p style="text-align:right;">Right paragraph.</p>
>> 改變文字字體*(font-family)* 樣式*(style)* ***其他字體需要可自行上網查詢***
>> <p style="font-family:courier;">This is a paragraph.</p>
>> 
> HTML格式化文本使用<pre>標籤定義
>
> HTML文字使用<a>標籤定義
>> 新增超連結屬性*(herf)* 
>> <a href="連結網址">This is a link</a> or <a href='連結網址'>This is a link</a>
>> 改變文字大小 *(font-size)* 樣式 *(Style)*
>> <a style="font-size:60px"> or <a style="font-size:2.5rem">
>> 新增背景顏色*(color))*樣式 *(style)*
>> <a style="background-color:DodgerBlue;"> 
>>
> HTML圖片使用<img>*(image)*標籤定義
>> 新增代替本文屬性*(alt)*與長*(height)*寬*(width)*屬性
>> <img src="圖片網址" alt="文字代替圖片" width="100" height="200"> or <img src='圖片網址' alt='文字代替圖片' width='100' height='200'>
>>
> HTML按鈕使用<button>標籤定義
>> 新增禁用屬性*(disabled)*
>> <button disabled>按鈕文字</button> 
>>
> HTML列表使用<ul> （無序/項目符號列表）或<ol>（有序/編號列表）標記定義，後跟<li> 標記（列表項）
>> <ul>                             <ol>
>>      <li>文字一</Li>                  <li>文字一</Li>
>>      <Li>文字二</Li>      or          <Li>文字二</Li>
>>      <Li>文字三</Li>                  <Li>文字三</Li>
>> </ul>                            </ol>
>>
> HTML換行使用<br>標籤定義
>
> HTML水平線使用<hr>*(Horizontal)*標籤定義
>
> HTML粗體使用<b>*(Bold)*標籤定義
>
> HTML重要文字使用<strong>標籤定義*消果跟<b>標籤效果差不多*
>
> HTML斜體文字使用<i>*(Italic)*標籤定義
>
> HTML強調文字使用<em>標籤定義*效果跟<i>標籤效果差不多*
>
> HTML標記文字使用<mark>標籤定義
>
> HTML刪除文字使用<del>標籤定義
>
> HTML插入文字使用<ins>標籤定義 *(baseline)*
>
> HTML下標文字使用<sub>標籤定義
>
> HTML上標文字使用<sup>標籤定義
>
> HTML縮小文字使用<small>標籤定義
>
> HTML短引號使用<q>標籤定義
>> <q>123</q> or 直接輸入 "123" *(個人推薦直接使用雙引號)*
>>
> HTML引用使用<blockquote>標籤定義
>> <blockquote city="引用網址">引用文字</blockquote>
>>
> HTML地址使用<address>標籤定義，元件通常顯示斜體
>> 個人不太使用此標籤，如果要達到斜體效果通常使用
>> <i>標籤 or <a style="font-style:italic">文字</a>
>>
>圖片位址 https://www.image-map.net/