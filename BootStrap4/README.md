# 簡介
> Bootstrap 4 是用於建立響應式、行動優先的網站，架設基礎利用RWD開發。[什麼是RWD](https://www.ibest.tw/page01.php)
> 
> [Bootstrap getting start](https://bootstrap.hexschool.com/docs/4.2/getting-started/download/)
>
# Grid基本
> 簡單來說Bootstrap的布局(grid)分為超小型、小型、中型、大型或超大型設備大小，而在以上裝置的布局都分為十二等分。   
> 以下圖舉例，滿版也就是12/12，bootstrap語法中就是col-*-12 ***星號為對應裝置***，換句話說螢幕的25%等於1/4，也就是col-*-3。   
> ![avatar](http://i.imgur.com/PS8H23s.png)   
>  超小型、小型、中型、大型或超大型設備規範如下圖。  
> ![avatar](http://i.imgur.com/thN8Dbq.png)  
# 對齊
> ### 垂直對齊   
> align-items-start (預設值，從頁面最上面開始)、 align-items-center (從頁面中間開始排序) 、align-items-end (從頁面最底部開始排序)，可參照下圖。    
> ![avatar](https://i.imgur.com/kZtfEsM.png)   
> align-self-start (預設值，從業面最左側開始)、 align-self-center (從頁面中間開始排序) 、align-self-end (從葉面最右側開始)。   
> ![avatar](http://i.imgur.com/azeyWua.png)   
> ### 水平對齊   
> justify-content-start：靠左對齊 、 justify-content-center：置中對齊 、 justify-content-end：靠右對齊 、 justify-content-around：分散對齊(含左右) 、 justify-content-between：分散對齊(不含左右)。
> ![avatar](http://i.imgur.com/ZPDggPx.png)  
> ### No gutters  
> 移除margin、padding。 ***ex /<div class/=/"row no-gutters/"/> /<//div/>***
> ![avatar](http://i.imgur.com/ClDKTyD.png)   
> ### Column wrapping   
> gird定義上把裝置布局分為十二等分，如果定義布局以col-9、col-4、col-6來佈局的話會分成兩列，因第一列9+4>12，故分為col-9為第一列，col-4、col-6第二列。   
> ![avatar](http://i.imgur.com/FsFj8Mc.png)   
> ### Column breaks   
> 只需要在要段行的地方加入/<div class=/"w-100/"/>/<//div/>，因w-100定義上就是佔據螢幕百分之百寬度，也就是12格布局，所以不管前面布局多少都會進行換行。   
> ![avatar](http://i.imgur.com/iUkALyx.png)   
> ### 重新排序   
> 使用.order-類來控制內容的可視順序(1~12、照數列排序)或是.order-first(第一)和.order-last(最後)。   

