# 網頁元件的定位    
|屬性|屬性名稱|設定值|
|----|:------|:-----|
|position|設定元件位置的排列方式|absolute(絕對定位)、relative(相對定位)、static(預設值)、fixed(固定)|
|width|指定元件寬度|寬度數值|
|height|指定元件高度|高度數值|
|left|指定元件與左邊界的距離(X座標)|距離數值|
|top|指定元件上邊界的距離(Y座標)|距離數值|
|overflow|超出邊界的顯示方式|距離數值|
|visibility|設定是否顯示|visible、hidden、inherit|

## 文繞圖效果 float
>  float (漂浮)屬性  
>> clear : 限制區塊左右有無 float 區塊 。   
>> none：預設值, 維持原排列方式。    
>> left：若左邊出現 float 區塊, 則將本區塊向下移, 直到 左邊沒有 float 區塊為止。   
>> right：若右邊出現 float 區塊, 則將本區塊向下移, 直 到右邊沒有 float 區塊為止。   
>> both：若左右任一邊出現 float 區塊,  則將本區塊向 下移,  直到兩邊都沒有 float 區塊為止 。   

## 圖層定位 z-index
> 指定元件之間的上下層次順序   
> z-index必須與position屬性一起使用。如果元件的z-index值相同，瀏覽 器會以程式順序層疊，程式後執行者會位於上方（back-to-front）    

## 設定超出邊界的顯示方式 Overflow
> 設定當元件內容超過元件的長度與寬度 時的呈現方式   
> 設定值有四種：    
>> visible：不管元件長寬，內容完全呈現。    
>> hidden：超出長寬的內容就不顯示。    
>> scroll：無論內容會不會超出長寬，都加入捲軸。    
>> auto：依狀況決定是否顯示捲軸。  