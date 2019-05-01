# 控制文字樣式   
|屬性|屬性名稱|設定值|
|----|-------|------|
|color|字體顏色|顏色名稱、16進位碼、RGB碼|
|font-family|指定字型樣式|字型名稱|
|font-size|字體大小|數值+百分比(%)、數值+單位(pt,px,em,ex)|
|font-style|文字斜體|normal(普通)、italic(斜體)、oblique(斜體)|
|font-weight|文字粗體|normal(普通)、bold(粗體)、bolder(超粗體)、lighter(細體)|   

## font-family 字型樣式
> 瀏覽器會依順序找尋系統中符合的字型   
> 字型名稱加上\"雙引號\"   
>> ex.  font-family: "Noto Sans TC","WenQuanYi Zen Hei","Heiti TC",Helvetica,"Microsoft YaHei","Microsoft JhengHei",Arial,sans-serif;    
> 引入字體 @font-face
>> ex.  @font-face { font-family: 字體名稱 ; src: url() }   
![avatar](http://i.imgur.com/3ZgCJTI.png)   
## font-size 字型大小   
> font-size: 字型大小+單位   
![avatar](http://i.imgur.com/jt0HQhM.png)   
## font-style 文字斜體   
> 設定值: normal, italic, oblique(斜體)   
## font-weight 文字粗體   
> 設定值:  normal|bold|bolder|lighter|number|initial|inherit;
## font-stretch 文字延展   
![avatar](http://i.imgur.com/NiMFZxZ.png)   
# 段落屬性   
|屬性|屬性名稱|設定值|
|----|-------|------|
|text-align|設定文字水平對齊|left、center、right、justify (分散對齊)|
|text-indent |首行縮排|數值＋百分比(%)數值＋單位|
|letter-spacing|設定字元間距normal數值+單位 (pt , px , em)|
|line-height|設定行高|數值＋單位|
|word-wrap|設定是否換行|break-word|
# 文字效果屬性   
|屬性|屬性名稱|設定值|
|----|-------|------|
|vertical-align|垂直對齊|baseline (一般位置)、super(上標字)、sub(下標字)、top(對齊頂端)、middle(垂直置中)、bottom(對齊底部)|
|text-decoration|增加裝飾樣式|none、underline(文字下方線)、line-through(刪除線)、overline(文字上方線)|
|text-transform|轉換字母大小寫|none、lowercase、uppercase、capitalize|
|text-shadow|增加陰影效果||