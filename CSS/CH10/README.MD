# 透明度 opacity   
> 指定HTML元素透明度   
> opacity: number (0~1)   
# 背景圖案設定
|   屬性  |     屬性名稱     | 設定值 |
|---------|:----------------|:------|
|background-image|背景圖案|url(圖案位址)|
|background-repeat|是否重複顯示背景圖案|repeat、repeat-x、repeat-y、no-repeat|
|background-attachment|背景圖案是否隨網頁卷軸捲動|fixed(固定)、scroll(隨卷軸捲動)|
|background-position|背景圖案位置|x% y%、x y 、[top,center,bottom] [left,center,right] |
|background|綜合應用||
|background-size |設定背景尺寸|length(長寬)、percentage(百分比)、cover(縮放至最小邊能符合元件)、contain(縮放至元素完全符合元件) |
|background-origin |設定背景原點 |padding-box、border-box、content-box |
|background-repeat |設定背景圖案是否重複 |repeat( 重複並排顯示,為預設值) 、 repeat-x (水平方向重複顯示) 、 repeat-y (垂直方向重複顯示) 、 no-repeat (不重複顯示) |    
# 設定背景漸層   
> linear-gradient: 線性漸層    
> radial-gradient: 放射性漸層    
> repeating-linear-gradient(): 指定重複線性漸層。   
> repeating-radial-gradient(): 指定重複放射狀漸層。    
>  linear-gradient(漸層方向, 色彩1, 位置1,色彩2,位置2....)    
>> 漸層方向: top/ left/ top left/ 角度deg (ex: 45deg表示左下到右上)    
> 產生gradient漸層語法輔助工具    
>> [ Ultimate CSS Gradient Generator](http://www.colorzilla.com/gradient-editor/)   
