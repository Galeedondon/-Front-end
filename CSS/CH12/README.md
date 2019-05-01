# 超連結設定   
> 尚未連結(link)   
> 已連結(visited)   
> 滑鼠移到連結時(hover)   
> 執行中(active)   

# 滑鼠游標特效
> ![avatar](http://i.imgur.com/pfFgmZQ.png)   

# 變形處理 - 2D變形函數   
|   2D變形函數  |     說明     | 範例|
|--------------|:-------------| :--|
|none          |定義不轉換。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_rotate&p=22)|
|matrix(n,n,n,n,n,n) |定義 2D 轉換，使用六個值的矩陣。| [範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_matrix)|
|translate(x,y)|定義 2D 轉換。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_translate)|
|translateX(x)|定義轉換，只是用 X 軸的值。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_translatex)|
|translateY(y) |定義轉換，只是用 Y 軸的值。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_translatey)|
|scale(x,y)|定義 2D 縮放轉換。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_scale)|
|scaleX(x) |通過設置 X 軸的值來定義縮放轉換。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_scalex)|
|scaleY(y)|通過設置 Y 軸的值來定義縮放轉換。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_scaley)|
|rotate(angle)|定義 2D 旋轉，在參數中規定角度。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_rotate)|
|skew(x-angle,y-angle)|定義沿著 X 和 Y 軸的 2D 傾斜轉換。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_skew)|
|skewX(angle)|定義沿著 X 軸的 2D 傾斜轉換。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_skewx)|
|skewY(angle)|定義沿著 Y 軸的 2D 傾斜轉換。|[範例](http://www.w3school.com.cn/tiy/c.asp?f=css_transform_skewy)|

# 濾鏡特效   
![avatar](http://i.imgur.com/o1FVTQy.png)   
>[範例](http://blog.shihshih.com/css-filter/)   

# 轉移特效 (Transition)
> transition-duration：指定轉移過程時間長度, 預設為 0 秒。   
> transition-delay：指定轉移延遲多久才開始,  預設為  0  秒。   
> transition-property：指定轉移的屬性, 預設為所有屬性。    
>  transition-timing-function：指定轉移過程的變化速率    
>> ease: 預設值, 以先快後慢的方式變化    
>> ease-in: 以先慢後快的方式變化    
>> ease-out: 同樣是先快後慢, 但變化速率與ease不同, 前段加速部份較 ease緩和    
>> linear:以一致的速度變化    

# 動畫特效 (Animation)
> animation-duration：動畫播放的時間長度。
> animation-delay：動畫延遲開始時間。 
> animation-timing-function：指定動畫播放過程各階段的 快慢 (與transition設定相同) 。
> animation-iteration-count：指定重複次數, 預設值為 1 。
> animation-name：設定『動畫名稱』,這個名稱必須另外用 @keyframes 命名規則。