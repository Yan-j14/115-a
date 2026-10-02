# Markdown 語法實作
## 一、標題
# H1
## H2
### H3
#### H4
##### H5
###### H6
---
## 二、文字樣式
+ 粗體：**粗體** 
+ 斜體：*斜體* 
+ 刪除線：~~刪除線~~
---
## 三、列表 
* Red
+ Green
- Blue
1. Bird
2. McHaie
3. Parish
---
## 四、引言區塊  
>新北市
>>板橋區
>>
>>中和區

>桃園縣
>>大溪鎮
>>
>>龜山鎮
---
## 五、程式碼區塊
`小區塊`
```
大區塊
```
`js`
```js
$scope.cookieGet=function(key){
   $scope.cookieResult = $cookieStore.get(key);
   console.log($scope.cookieResult);
}
```
`ruby`
```ruby
def index
puts "hello world"
end
```
`csharp`
```csharp
private void index(){
   MessageBox.Show("hello world");
}
```
---
## 六、連結
1. [高科大官網](https://www.nkust.edu.tw/)
2. <https://www.nkust.edu.tw/>
3. [GIT分支](/chapter_3_branch/git.html)
---
## 七、圖片
![NKUST](nkust.png "高科大")
---
## 八、表格
|Left-Aligned|Center Aligned|Right Aligned|
|:--- |:---:|---:|
|col 3 is|some wordy text|$1600|
|col 2 is|centered|$12|
|zebra stripes|are neat|$1|
|test|測試|$3333|
---
## 九、嵌入影片
[![推薦歌曲：艾薇 ft.吳霏-我受夠了](圖片.png)](https://www.youtube.com/watch?v=PGIbiZNXIks&list=RDPGIbiZNXIks&start_radio=1 "艾薇 ft.吳霏-我受夠了")
