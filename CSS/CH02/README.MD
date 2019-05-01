# 套用CSS樣式表—內嵌宣告  
> 內嵌宣告(Embedding)   
>> 標頭區域 \<head\>\<\/head\>   
>> 只能套用在單一網頁   
![avatar](http://i.imgur.com/bocDi6v.png)    
# 套用CSS樣式表—連結外部樣式   
> 連結外部樣式檔(Linking)   
>> CSS樣式存成獨立的檔案(*.CSS)   
>> 外部樣式檔的格式與內嵌宣告相同   
>> 省略\<style\>\<\/style\>標記   
>> 利用文字編輯工具來撰寫，再將檔案儲存為「檔名.CSS」，例如test.css。   
# 套用CSS樣式表—連結外部樣式   
> \<link\>
>> \<link rel=\"stylesheet\" type=\"text\/css\" href=\"test.css\"\>   
## CSS套用方式的優先順序   
> 三種宣告方式可以放在同一HTML文件中若有重複樣式時，優先順序為「行內宣告」>「內嵌宣告」>「連結外部樣式檔」   
# 認識CSS選擇器
> 標記名稱   
>> 相同標記皆套用相同樣式    
>> div \{ font\-size\: 16px\; color\: \#FFFFFF\;\}   
> 通用選擇器\(\*\)   
>> 不同標記皆可使用   
>> \* \{ font\-size\: 16px\; color\: \#ff0000\;\}   
# Class選擇器   
> 在HTML標記裡加入class屬性。
>> 例如: \<font class\=\"txt\"\>   
>> Class名稱不可使用HTML標記名稱   
> CSS樣式裡加入class選擇器宣告。   
>> .class屬性名 \{樣式規則\;\}   
# ID選擇器   
> 在HTML標記裡加入ID屬性。
>> \<font id\=\"font_bold\"\>   
> CSS樣式裡加入id選擇器宣告。   
>> \#id屬性名 \{樣式規則\;\}   
> 同一份HTML文件裡不能有重複ID名稱；Class名稱可重複   

# 屬性選擇器   
> 屬性(attribute)選擇器屬於進階篩選，用來篩選標記裡的屬性   
>> 例如: 想要指定超連結標記\<a\>的背景顏色為黃色，但是只套用在有target屬性的元件。   
>> a\[target\] \{ background-color\:yellow\; \}   
> 篩選方式有六種：
> |\[attribute \= \"value\"\]|屬性等於value|
> |\[attribute \~\= \"value\"\] |屬性包含完整value|
> |\[attribute \|\= \"value\"\]|屬性等於value或以value-開頭|
> |\[attribute \^\= \"value\"\]|屬性開頭有value|
> |\[attribute \$\= \"value\"\]|屬性最後有value|
> |\[attribute \*\= \"value\"\] |屬性有出現value|

