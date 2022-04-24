
<p align="center"><img src='https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG'></p>

# <p align="center"> Markdown 初階語法學習</p>
### <p align="center"> -->想要更順暢的使用Github?<--</p>
### <p align="center"> 那就必須學習如何使用Markdown語言!</p>
### <p align="center"> 接下來我們就來看看基本的Markdown語法~</p>

----------
## <p align="center"> Part1 -- Github環境介紹</p>
### 1. 創建專案:
 * 登入帳號-->點擊"Repositories"-->點擊右下方的"New"創建專案-->輸入想要的專案名稱-->點擊"Creat Repository"
![](https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/066.PNG)
### 2. 創建檔案:
 * 創建新檔案:點擊"Add file"-->選擇"Create new file"
 * 上傳檔案或資料夾:點擊"Add file"-->選擇" file"</p>
 
![](https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/061.PNG)
## <p align="center"> part2--基本語言</p>

* 初學者可以參考線上編輯裡的教學內容-->[Markdown線上編輯器-MdEditor](https://www.mdeditor.tw/)
* 但請留意有些Markdown的語法不適用於Github! 以下教學將以Github為主
<p><br></p>

## 1. 標題: `# + 空格`
# 標題示範
## 標題示範2
### 標題示範3
```
makedowm 寫法:

# 標題示範
## 標題示範2
### 標題示範3
```
<p><br></p>

## 2. 字體格式

~~刪除線~~ <br>
*斜體字*<br>
_斜體字_<br>
**粗體** <br> 
__粗體__<br>
***粗斜體***<br> 
___粗斜體___<br>

```
makedowm 寫法:

~~刪除線~~ 
*斜體字*
_斜體字_
**粗體** 
__粗體__
***粗斜體*** 
___粗斜體___
```
<p><br></p>


## 3. 點號: `* + 空格`
* 點號示範
* 1
* 2
* 3
```
makedowm 寫法:

* 點號示範
* 1
* 2
* 3
```
<p><br></p>

## 4. 編號: `數字. + 空格`

1. 示範1
2. 示範2
3. 示範3

```
makedowm 寫法:

1. 示範1
2. 示範2
3. 示範3
```
<p><br></p>

## 5. 橫線:```-----``` 、 開頭直線: ``` > + 空格 + <br>```

* ```<br>```代表換行

-------

> 示範2<br>
> 示範3<br>

```
makedowm 寫法:

-------

> 示範2<br>
> 示範3<br>
```
<p><br></p>

## 6. 表格: `| + ---`

* ----: =靠右
* :---- =靠左
* ----- =置中

| First   | Second  |
| ------: | ------: |
| Content | Content |
| Content | Content |

```
makedowm 寫法:

| First   | Second  |
| ------: | ------: |
| Content | Content |
| Content | Content |
```
<p><br></p>

## 7. 網址: ```[文字描述](網址)``` 

* 2種寫法，分為顯示網址與不顯示網址

[點擊前往](https://www.mdeditor.tw/)<br>
https://www.mdeditor.tw/
```
makedowm 寫法: 

[點擊前往](https://www.mdeditor.tw/)
https://www.mdeditor.tw/

* 補充:文字描述可空白
```
<p><br></p>

## 8. 圖片放置: ```![文字描述](網址)```

* 可先將圖片"Uload file"上Github，因為必須使用"網址"才可放置圖片
* 想取得圖片網址，可以對圖片點擊滑鼠右鍵，選擇"在分頁中開啟"，接著複製網址即可

![示範照片](https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG)

```
makedowm 寫法: 

![示範照片](https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG)

* 補充:文字描述可空白
```
<p><br></p>

## 9. 文字位置: ```<p align="center">文字</p>```

<p align="center">1.center=置中</p>

<p align="left">2.left=置左</p>

<p align="right">3.right=置右</p>

```
makedowm 寫法: 

<p align="center">1.center=置中</p>

<p align="left">2.left=置左</p>

<p align="right">3.right=置右</p>

```
<p><br></p>

## 10. 圖片位置: ```<p align="center"><img src="圖片網址"></p>```
* 置中=center 、 置左(預設)=left、 置右=right
<p align="center"><img src='https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG'></p>

```
makedowm 寫法: 

<p align="center"><img src='https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG'></p>

```
<p><br></p>

## 11. 圖片大小: ```<p align="center"><img src="圖片網址" width="20%" height="20%"></p>```
* width=寬 height=高
* width=20% :調取圖片比例(寬)變成20%
* width=20px :像素，調取圖片呈現大小(寬)，會因屏幕解析度不同有所差異

<p align="center"><img src='https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG' width="20%" height="20%"></p>

<p align="center"><img src='https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG' width="20px"></p>


```
makedowm 寫法: 

<p align="center"><img src='https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG' width="20%" height="20%"></p>

<p align="center"><img src='https://raw.githubusercontent.com/luoyan109/markdown-learning/main/img/06.PNG' width="20px"></p>

```
<p><br></p>

### <p align="center">文章待續...</p>

<p><br></p>

<p align="center">資料參考:</p>

<p align="center">這一次要幫你徹底搞明白px、ppi、dot、dpi、sp、dp、pt<br>
原文網址：https://kknews.cc/news/meo42p9.html</p>

<p align="center">Markdown線上編輯器-MdEditor<br>
原文網址：https://www.mdeditor.tw/</p>

